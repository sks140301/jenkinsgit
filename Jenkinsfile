pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh '$PWD'
          }
        }

        stage('task 2') {
          steps {
            echo 'Hello world'
          }
        }

      }
    }

  }
}