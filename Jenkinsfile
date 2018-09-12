pipeline {
  agent any
  stages {
    stage('error') {
      environment {
        dddff = ''
      }
      steps {
        echo '${env.ImageName}'
        sh '''adfadf
adfader'''
        sh 'ssss'
        junit(testResults: 'ddd', allowEmptyResults: true, keepLongStdio: true)
        cleanWs(cleanWhenNotBuilt: true, notFailBuild: true)
        archiveArtifacts(artifacts: 'dddd', allowEmptyArchive: true, caseSensitive: true)
      }
    }
  }
  environment {
    ImageName = 'ddd'
  }
}