pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'automation-test-strict'
      }
    }
  }
}