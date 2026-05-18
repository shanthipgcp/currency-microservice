pipeline {
    agent {
        label 'java-workernode'
    }
    environment {
        // setting environment variable  key value ${key}
        name = "Arjun Preeth"
        course = "Jenkins"
    }
    stages {
        stage ('FirstStage') {
            environment {
                cloud = "GCP"
            }
            steps {
                echo "welcome ${name}"
                echo "you have enrolled to ${course} course"
                echo "you are certified in ${cloud} cloud"
            }
        }
    }
}  
