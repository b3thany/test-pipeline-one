pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello, world!'
        script {
          publishEvent simpleEvent('Frobulate')
        }

      }
    }
  }
}