pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}