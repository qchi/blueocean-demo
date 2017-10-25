pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        sh 'echo "First stage: first step"'
        echo 'First stage: second step'
      }
    }
    stage('Second stage') {
      steps {
        echo 'Second stage: first step'
        sh 'echo "Second stage: second step"'
      }
    }
  }
}