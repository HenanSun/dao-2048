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
        input(message: 'Should we continue?', ok: 'Yes, we should.', submitter: 'miaoyun_admin')
      }
    }
  }
}