pipeline {
  agent {
    docker {
      image 'ubuntu'
    }

  }
  stages {
    stage('Stage 1') {
      steps {
        sh 'cat /etc/issue'
      }
    }
  }
}