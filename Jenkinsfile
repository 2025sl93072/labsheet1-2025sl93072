pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/https://github.com/2025sl93072/labsheet1-2025sl93072.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 calculator.py'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploy stage (will update later)"'
            }
        }
    }
}

