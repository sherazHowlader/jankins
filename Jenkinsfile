pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        winpty php --version
      }
    }
    stage('hello') {
      steps {
        winpty php hello.php
      }
    }
  }
}
