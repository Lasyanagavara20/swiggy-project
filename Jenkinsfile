pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo 'Checking out source code from GitHub'
            }
        }

        stage('Build with Maven') {
            steps {
                echo 'Building Swiggy application (Maven simulation)'
            }
        }

        stage('SonarQube Analysis') {
            steps {
                echo 'Running SonarQube analysis (simulation)'
            }
        }

        stage('Build Docker Image') {
            steps {
                echo 'Building Docker image (simulation)'
            }
        }

        stage('Push Docker Image') {
            steps {
                echo 'Pushing Docker image to registry (simulation)'
            }
        }
    }
}
