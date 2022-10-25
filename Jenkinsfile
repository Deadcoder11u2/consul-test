pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          echo 'Building'
            sh 'echo HELLO WORLD'
        }
      }
      stage('Deploy') {
        steps {
          echo "Deploying"
            sh 'chmod +x gradlew && ./gradlew test --scan -s'
        }
      }
    }
}
