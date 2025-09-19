pipeline {
  agent any
  stages {
    stage('Build') {
      steps { echo 'Compiling and packaging project...' }
    }
    stage('Unit & Integration Tests') {
      steps { echo 'Running unit and integration tests...' }
    }
    stage('Code Analysis') {
      steps { echo 'Performing static code analysis...' }
    }
    stage('Security Scan') {
      steps { echo 'Running security scan...' }
    }
    stage('Deploy to Staging') {
      steps { echo 'Deploying to staging environment...' }
    }
    stage('Integration Tests on Staging') {
      steps { echo 'Running integration tests in staging...' }
    }
    stage('Deploy to Production') {
      steps { echo 'Deploying to production environment...' }
    }
  }
}
