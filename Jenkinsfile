pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('ci') {
      steps {
        sh 'echo "this is test"'
        echo 'hello'
      }
    }
  }
}