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
        sleep(unit: 'MILLISECONDS', time: 1)
      }
    }

    stage('Component Test') {
      steps {
        echo 'Component Testiong...'
        sleep 1
      }
    }

    stage('Integration Test') {
      steps {
        echo 'Integration Testing...'
        sleep(unit: 'SECONDS', time: 10)
      }
    }

    stage('UI Test') {
      steps {
        echo 'UI Testing...'
        sleep(time: 1, unit: 'MINUTES')
      }
    }

  }
}