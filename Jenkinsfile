pipeline {
  agent any

  stages {
    stage('principal') {
      steps {
        build job: 'invocado', wait: true
      }
    }
  }
}
