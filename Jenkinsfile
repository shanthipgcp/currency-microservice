pipeline {
    agent {
        label 'java-workernode'
    }
    environment {
        // setting environment variable  key value ${key}
        name = "shiva"
        course = "Jenkins"
    }
    stages {
        stage ('FirstStage') {
            steps {
                echo "welcome ${name}"
                echo "you have enrolled to ${course} course"
            }
        }
    }
}  
