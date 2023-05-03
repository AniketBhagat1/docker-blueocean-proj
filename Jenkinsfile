pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Git Checkout') {
      steps {
        sh 'git clone \'https://github.com/AniketBhagat1/Dockerfile.git\''
      }
    }

    stage('Build-img') {
      steps {
        sh 'sudo docker build -t aniketbhagat1997/apache_img:1.5 .'
      }
    }

  }
}