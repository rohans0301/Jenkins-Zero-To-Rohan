pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'docker run node:16-alpine'
        sh 'docker ps -a'
        sh 'node --version'
      }
    }
  }
}
