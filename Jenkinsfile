pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'Hello'
          }
        }

        stage('test') {
          steps {
            sh 'echo "hello"'
          }
        }

      }
    }

    stage('stage2') {
      steps {
        echo 'step2'
      }
    }

    stage('stage3') {
      steps {
        echo 'step3'
      }
    }

  }
}