pipeline {
    agent any
    stages {
        stage('Build') { steps { echo 'Building project...' } }
        stage('Unit Tests') { steps { echo 'Running tests...' } }
        stage('Code Analysis') { steps { echo 'Analyzing code...' } }
        stage('Security Scan') { steps { echo 'Scanning for vulnerabilities...' } }
        stage('Deploy to Staging') { steps { echo 'Deploying to Staging...' } }
        stage('Staging Tests') { steps { echo 'Testing on Staging...' } }
        stage('Deploy to Production') { steps { echo 'Deploying to Production...' } }
    }
}
