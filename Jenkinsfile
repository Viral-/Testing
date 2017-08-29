pipeline {
  agent {
    node {
      label 'docker'
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo 'building'
      }
    }
  }
  environment {
    foo = '1'
  }
}