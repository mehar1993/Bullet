pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('Display') {
      steps {
        ws(dir: '/opt/Jenkins') {
          timestamps() {
            echo 'Welcome to Jenkins'
          }
  
        }

      }
    }

  }
}