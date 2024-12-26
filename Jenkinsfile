node {
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing...'
        script {
          if (currentBuild.result == 'SUCCESS') {
            echo 'Looks good'
          } else {
            echo 'failed!'
          }
        }
      }
    }
  }
}
