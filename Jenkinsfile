pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'echo "Hello World !!" '
          }
        }

        stage('Test1') {
          steps {
            sleep 5
          }
        }

      }
    }

  }
}