pipeline {
  agent {
    docker {
      image '3-jdk-12-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'hello\''
      }
    }
  }
}