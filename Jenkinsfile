pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            sh 'go test ./...'
          }
        }

        stage('') {
          steps {
            echo 'hello branch 2'
          }
        }

      }
    }

  }
}