pipeline {
  agent any
/*
  triggers {
    cron('* * * * *')
  }
*/
  stages {
    stage('principal') {
      steps {
        build job: 'invocado', wait: true, parameters: [string(name: 'DATA', value: 'desde aca')]
      }
    }
  }
}
