pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'mvn install', propagate: true)
      }
    }
  }
  environment {
    Dev = ''
  }
}