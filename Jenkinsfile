pipeline {
  agent any
  stages {
    stage('nanka1') {
      environment {
        nanka = 'val'
      }
      parallel {
        stage('nanka2') {
          steps {
            timestamps() {
              sleep 10
            }
            
          }
        }
        stage('hoge1') {
          steps {
            sh 'echo \'hoge\''
            sleep 3
          }
        }
      }
    }
    stage('fuga') {
      steps {
        sh 'echo \'fuga\''
        sleep 10
      }
    }
  }
}