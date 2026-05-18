pipeline {
    agent {
        label 'java-workernode'
    }
    stages {
        stage('Buid') {
            steps {
                echo "build stage from hotfix branch"
            }
        }
        stage('Scans') {
            steps {
                echo "scan stage from hotfix branch"
            }
        }
        stage('dockerBuild') {
            steps {
                echo "docker build stage from hotfix branch"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy stage from hotfix branch"
            }
        }
    }
}
