pipeline {
  agent {
    node {
      label 'af'
    }

  }
  stages {
    stage('Buzz Build') {
      steps {
        sleep 15
        sh 'chmod +x ./jenkins/*.sh'
        sh './jenkins/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}