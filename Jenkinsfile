pipeline {
  agent any
  stages {
    stage('st1') {
      steps {
        build(job: 'j1', quietPeriod: 1, wait: true)
      }
    }
  }
}