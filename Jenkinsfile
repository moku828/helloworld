pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'gcc -o helloworld main.cpp'
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