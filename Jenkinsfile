pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        node(label: 'node')
        sh '''
echo "building..."

npm start'''
      }
    }

  }
}