pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Build_img') {
      steps {
        sh 'sudo docker build -t aniketbhagat1997/apache_img:4.0 .'
      }
    }

  }
}