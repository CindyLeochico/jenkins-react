pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker { 
                    image 'node:20.17.0-alpine' 
                }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}