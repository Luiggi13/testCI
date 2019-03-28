pipeline {
  agent any
  stages {
    stage('commited') {
      parallel {
        stage('commited') {
          steps {
            mail(subject: 'Mail from jenkins', body: 'Ha funcionado', cc: 'christian.llansola@outlook.es', bcc: 'christian.llansola@gmail.com', from: 'christian.llansola@gmail.com', replyTo: 'christian.llansola@gmail.com', to: 'christian.llansola@gmail.com')
          }
        }
        stage('fsd') {
          steps {
            echo 'funciona'
          }
        }
      }
    }
  }
}