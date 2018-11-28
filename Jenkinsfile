pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        echo 'test2'
      }
    }
    stage('error') {
      steps {
        input 'Should we continue?'
      }
    }
  }
}