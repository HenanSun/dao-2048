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
        cleanWs(cleanWhenAborted: true, cleanWhenFailure: true, cleanWhenNotBuilt: true, cleanWhenSuccess: true, cleanWhenUnstable: true, cleanupMatrixParent: true, deleteDirs: true)
      }
    }
  }
  environment {
    ImageName = 'ddd'
  }
}