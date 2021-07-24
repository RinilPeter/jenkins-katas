pipeline {
  agent any
  stages {
    stage('Par exec') {
      parallel {
        stage('Say hello') {
          steps {
            sh 'echo " Hi hello world"'
          }
        }
      }
    }

  }
}
