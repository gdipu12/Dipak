pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'app deployment build image'
      }
    }

    stage('stage2') {
      steps {
        sh 'push to registry'
      }
    }

    stage('stage3 ') {
      steps {
        sh 'app deployment'
      }
    }

  }
}