pipeline {
  agent {
    docker {
      image 'node:6'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Bulid') {
      steps {
        sh 'npm install'
      }
    }
  }
}