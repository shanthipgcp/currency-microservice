// parameters
pipeline {
    agent {
        label 'java-workernode'
    }

    // tools {

    // }

    // environment {

    // }

    parameters {
        string(name: 'APPLICATION_NAME', defaultValue: 'my-app', description: 'Name of the application')
        booleanParam(name: 'RUN_TESTS', defaultValue: true, description: 'would you like to run tests, buddy?')
        choice(name: 'ENV', description: 'Select the environment', choices: ['dev', 'test', 'prod'])
        password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter the password')
    }

    stages {
        stage('Parameters') {
            steps {
                // code for parameters
                echo "My app name is ${params.APPLICATION_NAME}"
                echo "Do you want to run tests? ${params.RUN_TESTS}"
                echo "Deploying into the ${params.ENV} environment"
                echo "The password is ${params.PASSWORD}"
            }
        }
    }
}
