pipeline {
    agent {
        docker { image 'golang:alpine' }
    }
    stages {
        stage('Show Go Version') {
            steps {
                sh 'go version'
            }
        }
    }
}