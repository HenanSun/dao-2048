pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'make'
        echo 'eee'
        git(url: 'https://github.com/HenanSun/dao-2048', branch: 'master')
      }
    }
  }
}