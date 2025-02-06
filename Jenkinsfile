pipeline {
     agent any

  stages {
    stage('Build') {
        steps {
            echo "hallo build"
        }
    }
     stage('test') {
        steps {
            echo "hallo test"
        }
     }
  }

  post {
    always {
      echo "dont worry"
    }
    success {
      echo "saya sukses"
    }
    failure {
      echo "gagal"
    }
  }
    
