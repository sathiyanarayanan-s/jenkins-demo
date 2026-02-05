pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }
    }

    post {
        success {
            echo 'Build completed successfully'
        }
        failure {
            echo 'Build failed'
        }
    }
}
