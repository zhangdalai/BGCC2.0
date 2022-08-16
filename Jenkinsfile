pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            sleep 10
          }
        }

        stage('1-1') {
          steps {
            node(label: '123')
          }
        }

      }
    }

    stage('2') {
      steps {
        echo '123213'
      }
    }

  }
}