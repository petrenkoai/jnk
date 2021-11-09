pipeline {
  agent {
    node {
      label 'af'
    }

  }
  stages {
    stage('Buzz Build') {
      steps {
        pwd()
      }
    }

    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}