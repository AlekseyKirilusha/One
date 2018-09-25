pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6.3'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
      }
    }
  }
}