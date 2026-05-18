pipeline {
    agent {
        label 'java-workernode'
    }
    stages {
        stage('Buid') {
            steps {
                echo "build stage from main branch"
            }
        }
        stage('Scans') {
            steps {
                echo "scan stage from main branch"
            }
        }
        stage('dockerBuild') {
            steps {
                echo "docker build stage from main branch"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy stage from main branch"
            }
        }
    }
}
