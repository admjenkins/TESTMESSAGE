pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('TEST') {
      steps {
        echo 'HELLO ITS A TEST'
      }
    }

    stage('BUILD') {
      steps {
        echo 'ITS THE BUILD PART'
      }
    }

    stage('DEPLOY') {
      steps {
        echo 'ITS THE DEPOLYMNT PART'
      }
    }

  }
}