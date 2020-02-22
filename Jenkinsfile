pipeline {
  agent {
    docker {
      image '1822d5eeb0f6'
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