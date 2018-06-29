pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build 'git'
      }
    }
    stage('test') {
      agent any
      steps {
        build 'git'
      }
    }
  }
}