pipeline {
  agent {
    node {
      label 'dockeryet'
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