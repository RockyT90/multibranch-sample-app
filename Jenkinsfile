pipeline {
  agent any
  parameters {
        choice(name: 'Target', choices: ['Web Server', 'Background Job'], description: 'Select Target')
    }
  stages {
    stage('Build') {
      steps {
        echo Building
        echo "Building ${params.Target}"
      }
    }
    stage('Test') {
      steps {
        echo "Testing"
      }
    }
    stage('deploy') {
      steps {
        echo "Deploy"
      }
    }
  }
}
