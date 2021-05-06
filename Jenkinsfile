pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        echo 'Linting....'
        sleep(unit: 'MICROSECONDS', time: 1)
      }
    }

    stage('Unit Test') {
      steps {
        echo 'Unit Testing,,,,'
        sleep(unit: 'SECONDS', time: 4)
      }
    }

    stage('Component Test') {
      steps {
        echo 'Component Testiong...'
      }
    }

    stage('Integration Test') {
      steps {
        echo 'Integration Testing...'
      }
    }

    stage('UI Test') {
      steps {
        echo 'UI Testing...'
      }
    }

  }
}