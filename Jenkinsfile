pipeline {
  agent {
    docker {
      image 'node:10.22.0-alpine3.9'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}