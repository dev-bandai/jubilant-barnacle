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
          }
        }
      }
    }
  }
}