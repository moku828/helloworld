pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'gcc -o helloworld helloworld.cpp'
      }
    }
    stage('ls') {
      steps {
        sh 'ls'
      }
    }
  }
}