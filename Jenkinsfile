pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
    stage('Build') {
      steps {
        echo 'Build triggered by GitHub webhook ✅'
      }
    }
  }
}
