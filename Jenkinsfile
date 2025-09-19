pipeline {
  agent any
  stages {
    stage('Rise') {
      steps {
        echo 'Starting stage 1'
        sh 'bash -c "whoami"'
        echo 'Finished stage 1'
      }
    }

    stage('Shine') {
      steps {
        echo 'Shining'
        sh 'bash -c "echo $SHELL"'
        echo 'Shined'
      }
    }

  }
}