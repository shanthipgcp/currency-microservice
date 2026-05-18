pipeline {
    agent {
        label 'java-workernode'
    }
    stages {
        stage('Buid') {
            steps {
                echo "build stage from testing branch"
            }
        }
        stage('Scans') {
            steps {
                echo "scan stage from testing branch"
            }
        }
        stage('dockerBuild') {
            steps {
                echo "docker build stage from testing branch"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy stage from testing branch"
            }
        }
    }
}
