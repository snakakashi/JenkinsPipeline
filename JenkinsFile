pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building the code using Maven to compile and package the application"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Running unit tests using JUnit"
                echo "Running integration tests using Selenium"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Analysing code quality using SonarQube"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Performing security scan using OWASP ZAP"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Deploying application to staging server on AWS EC2"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Running integration tests on staging environment using Selenium"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Deploying application to production server on AWS EC2"
            }
        }

    }
}
