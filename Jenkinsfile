pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Unit and Integration Tests: JUnit / Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Tests on Staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production'
            }
        }
    }
}