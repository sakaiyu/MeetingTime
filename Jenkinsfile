pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('Test') {
            steps {
                echo 'testing...'
                sh 'npm test'
            }
        }
    }
}
