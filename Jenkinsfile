pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'hello-world'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}