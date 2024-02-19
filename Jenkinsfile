pipeline {
  agent any
  stages {
    stage('first stage') {
      parallel {
        stage('first stage') {
          steps {
            echo 'hello world'
          }
        }

        stage('second syage') {
          steps {
            echo 'yooo'
          }
        }

      }
    }

  }
}