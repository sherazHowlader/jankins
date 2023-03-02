pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        sh 'php --version'
      }
    }
    stage('hello') {
      steps {
        winpty php hello.php
      }
    }
  }
}