pipeline {
    agent {
        docker { image 'gcc:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'gcc --version'
            }
        }
    }
}