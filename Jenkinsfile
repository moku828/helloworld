pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'g++ -o helloworld main.cpp'
          }
        }
        stage('ls') {
          steps {
            sh 'ls'
          }
        }
      }
    }
  }
}