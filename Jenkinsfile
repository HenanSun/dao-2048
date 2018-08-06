pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'make'
        echo 'eee'
        git(url: 'https://github.com/HenanSun/dao-2048', branch: 'master')
        archiveArtifacts(artifacts: '/out', allowEmptyArchive: true, caseSensitive: true, defaultExcludes: true, excludes: '/out/i*', fingerprint: true, onlyIfSuccessful: true)
        git(url: 'ssss', branch: 'master', changelog: true, credentialsId: 'ssss', poll: true)
      }
    }
  }
}