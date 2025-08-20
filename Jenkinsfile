pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step (learning phase, nothing here yet)'
                bat 'echo Deploying...'
            }
        }
    }
}
