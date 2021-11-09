pipeline {
  agent {
    node {
      label 'af'
    }

  }
  stages {
    stage('Buzz Build') {
      steps {
        sh 'pwww'
      }
    }

    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}