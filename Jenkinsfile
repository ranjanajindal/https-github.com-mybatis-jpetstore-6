pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Maven Build', propagate: true)
      }
    }
  }
  environment {
    Dev = ''
  }
}