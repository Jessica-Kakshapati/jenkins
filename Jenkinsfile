pipeline {
    agent any
    stages {
        stage('Build') { steps { echo 'Building project...' } }
        stage('Unit and Integration Tests') { steps { echo 'Running tests...' } }
        stage('Code Analysis') { steps { echo 'Analyzing code with SonarQube...' } }
        stage('Security Scan') { steps { echo 'Running OWASP Dependency-Check...' } }
        stage('Deploy to Staging') { steps { echo 'Deploying to Staging...' } }
        stage('Integration Tests on Staging') { steps { echo 'Running tests on Staging...' } }
        stage('Deploy to Production') { steps { echo 'Deploying to Production...' } }
    }
}
