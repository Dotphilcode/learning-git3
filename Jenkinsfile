pipeline {
  agent any
  stages {
    stage('echo') {
      parallel {
        stage('echo') {
          steps {
            echo 'hello my friend'
          }
        }

        stage('echo 2') {
          steps {
            echo 'hello again'
          }
        }

      }
    }

  }
}