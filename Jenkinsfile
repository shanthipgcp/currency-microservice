pipeline {
    agent {
        label 'java-workernode'
    }
    environment {
        // setting environment variable  key value ${key}
        name = "shiva"
        course = "Jenkins"
        SONAR_CREDS = credentials('sonar_creds')
    }
    stages {
        stage ('FirstStage') {
            environment {
                name = "shanthi"
                cloud = "GCP"
            }
            steps {
                echo "welcome ${name}"
                echo "you have enrolled to ${course} course"
                echo "you are certified in ${cloud} cloud"
            }
        }
        stage ('SecondStage') {
            steps {
                echo "welcome ${name}"
                echo "you have enrolled to ${course} course"
                // cloud variable is not accessible here as it is defined in first stage
                echo "you are certified in ${cloud} cloud"
                echo "sonar creds username is ${SONAR_CREDS}"
            }
        }
    }
}  
