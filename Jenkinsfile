pipeline {
  agent any

  stages {
    stage('principal') {
      steps {
        build job: 'invocado', wait: true, parameters: [string(name: 'DATA', value: 'desde aca')]
      }
    }
  }
}
