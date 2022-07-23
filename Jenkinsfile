pipeline {
    agent {
        docker { image 'debian:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'uname -a'
            }
        }
    }
}