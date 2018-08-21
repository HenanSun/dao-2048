pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        echo '${env.ImageName}'
        git(url: 'https://github.com/HenanSun/dao-2048', branch: 'test-icon', changelog: true, credentialsId: 'ssss', poll: true)
        archiveArtifacts(artifacts: '/out', allowEmptyArchive: true, caseSensitive: true, defaultExcludes: true, excludes: '/out/i*', fingerprint: true, onlyIfSuccessful: true)
        cleanWs(cleanWhenFailure: true, cleanWhenNotBuilt: true, cleanWhenSuccess: true, cleanWhenAborted: true, cleanWhenUnstable: true, cleanupMatrixParent: true, deleteDirs: true, externalDelete: 'dder', notFailBuild: true, skipWhenFailed: true)
        script {
          sssdsad
        }

        svn(url: 'ddd', changelog: true, poll: true)
      }
    }
  }
  environment {
    ImageName = 'ddd'
  }
}