pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analysing code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security scan using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS EC2 Staging'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Selenium integration tests'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS EC2 Production'
            }
        }
    }
}
