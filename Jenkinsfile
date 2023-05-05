pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Build_img') {
      steps {
        sh 'sudo docker images'
      }
    }

  }
}