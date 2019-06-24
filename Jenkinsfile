pipeline {
  agent any
  stages {
    stage('testing pipeline') {
      steps {
        echo 'test1'
        sh 'mkdir from-jenkins'
        mail(subject: 'test pipeline', body: 'testing blue ocean', from: 'ayswarya.ashok@ducenit.com', replyTo: 'princy.catharine@ducenit.com', to: 'princy.catharine@ducenit.com')
      }
    }
  }
}