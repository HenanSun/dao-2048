pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'qqq'
        sh '''adfadf
adfader'''
        sh 'ssss'
        junit(testResults: 'ddd', allowEmptyResults: true, keepLongStdio: true)
        cleanWs()
      }
    }
  }
  environment {
    ImageName = 'ddd'
  }
}