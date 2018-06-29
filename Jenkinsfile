pipeline {
  agent {
    node {
      label 'ci_cd'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'git'
      }
    }
  }
}