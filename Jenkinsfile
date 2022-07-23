pipeline {
    agent {
        docker { image 'debian:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'cat /etc/debian_version'
            }
        }
    }
}