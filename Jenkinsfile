pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                sh 'gradle build'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deployin"
            }
        }
    }
}
