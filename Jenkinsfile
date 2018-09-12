pipeline {
  agent {
    docker {
      image 'ubuntu:16.04'
    }

  }
  stages {
    stage('error') {
      steps {
        input(message: 'asd', ok: 'y')
      }
    }
  }
}