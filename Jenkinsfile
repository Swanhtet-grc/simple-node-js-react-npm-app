pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd simple-node-js-react-npm-app
echo "building..."'''
      }
    }

    stage('') {
      steps {
        sh '''npm start
echo "done"'''
      }
    }

  }
}