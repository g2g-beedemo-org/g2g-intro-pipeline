pipeline {
  agent {
    node {
      label 'jdk9'
    }
    
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello world!'
        sh 'java -version'
      }
    }
  }
}