pipeline {
  agent any
  stages {
    stage('install and build') {
      steps {
        sh 'npm i'
      }
    }
    stage('testsmsnotify') {
      steps {
        sh 'node .'
      }
    }
  }
}