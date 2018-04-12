pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('pre-prod') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}