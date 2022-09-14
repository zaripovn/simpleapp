pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('error') {
      agent any
      steps {
        echo 'Hello world!'
      }
    }

  }
}