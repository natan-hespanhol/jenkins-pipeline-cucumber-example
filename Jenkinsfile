pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building...'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing...'
          }
        }

      }
    }

    stage('Generate Reports') {
      steps {
        echo 'Generating reports'
      }
    }

    stage('Alert to Email') {
      steps {
        echo 'Alert informing the execution sent to Email'
      }
    }

  }
}