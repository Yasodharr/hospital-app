pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code from GitHub...'
            }
        }
        stage('Build Frontend') {
            steps {
                echo 'Building Hospital Frontend UI...'
                bat 'cd frontend && dir'
            }
        }
        stage('Build Backend') {
            steps {
                echo 'Building Hospital Backend Services...'
                bat 'cd backend && dir'
            }
        }
        stage('Run Tests') {
            steps {
                echo 'Running Automated Tests for Patient Portal...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Hospital App to Staging Environment...'
            }
        }
    }
}