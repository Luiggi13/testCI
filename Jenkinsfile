pipeline {
  agent any
  stages {
    stage('commited') {
      parallel {
        stage('commited') {
          steps {
            git(url: 'https://github.com/Luiggi13/testCI', branch: 'master', changelog: true, poll: true, credentialsId: 'Luiggi13')
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