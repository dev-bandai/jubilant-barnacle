pipeline {
  agent any
  stages {
    stage('nanka') {
      parallel {
        stage('nanka') {
          steps {
            timestamps() {
              sleep 10
            }
            
          }
        }
        stage('hoge') {
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