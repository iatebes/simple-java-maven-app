pipeline {
  agent {
    docker {
      image 'maven'
      args '-v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven'
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