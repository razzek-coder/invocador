pipeline {
  agent any

  stages {
    stage('principal') {
      steps {
        build job: 'invocado', wait: false, parameters: [string(name: 'DATA', value: 'desde aca')]
      }
    }
  }
}
