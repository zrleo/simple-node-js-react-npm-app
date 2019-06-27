pipeline {
  agent none
  stages {
    stage('Bulid') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      environment {
        CI = 'True'
      }
      steps {
        sh 'echo "test"'
      }
    }
  }
}