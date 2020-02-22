pipeline {
  agent {
    docker {
      image '1822d5eeb0f6'
      args '-p 8080:8080'
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