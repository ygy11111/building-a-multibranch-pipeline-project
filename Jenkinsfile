pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello world!"'
            echo 'hahaha'
          }
        }

        stage('suibian') {
          steps {
            echo 'buzhidao'
          }
        }

      }
    }

    stage('deployment') {
      steps {
        sh 'echo "Hello world! devops"'
      }
    }

  }
}