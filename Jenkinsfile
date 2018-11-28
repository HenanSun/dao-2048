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
        input(message: 'Should we continue?', parameters: [
         [$class: 'TextParameterDefinition', defaultValue: 'Henan', description: 'Who should I say hello to?', name: 'PERSON'],
         [$class: 'TextParameterDefinition', defaultValue: 'Jenkins', description: 'Who else should I say hello to?', name: 'PERSON1']
        ])
      }
    }
  }
}
