pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project using Maven...'
                echo 'This is a new print message for checking...'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests using JUnit and Selenium...'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyzing code with SonarQube...'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning code for security issues using OWASP Dependency-Check...'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to staging environment (e.g., AWS EC2)...'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging using Selenium...'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production environment (e.g., AWS EC2)...'
            }
        }
    }
}
