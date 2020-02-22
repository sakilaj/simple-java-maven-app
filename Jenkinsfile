pipeline {
  agent {
    docker {
      args '-p 8080:8080'
      image 'cd14cecfdb3a'
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