pipeline {
  agent any
  stages {
    stage('load account name') {
      parallel {
        stage('load account name') {
          steps {
            sh 'echo test'
          }
        }
        stage('erdddd') {
          steps {
            echo 'test'
          }
        }
        stage('error') {
          steps {
            input(message: 'test', id: 'ssss', ok: 'sssss')
          }
        }
      }
    }
  }
}