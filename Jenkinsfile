pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "hello world"'
          }
        }

        stage('stage2') {
          steps {
            echo 'My message'
          }
        }

      }
    }

  }
}