pipeline {
    agent {
        label 'java-workernode'
    }
    stages {
        stage('Buid') {
            steps {
                echo "build stage from feature branch"
            }
        }
        stage('Scans') {
            steps {
                echo "scan stage from feature branch"
            }
        }
        stage('dockerBuild') {
            steps {
                echo "docker build stage from feature branch"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy stage from feature branch"
            }
        }
    }
}
