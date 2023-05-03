pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Build_img') {
      steps {
        sh 'docker build -t aniketbhagat1997/apache_img:4.0 .'
      }
    }

  }
}