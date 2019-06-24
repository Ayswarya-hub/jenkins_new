pipeline {
  agent any
  stages {
    stage('testing pipeline') {
      parallel {
        stage('testing pipeline') {
          steps {
            echo 'test1'
          }
        }
        stage('BUILD') {
          steps {
            sleep 10
          }
        }
      }
    }
  }
}
