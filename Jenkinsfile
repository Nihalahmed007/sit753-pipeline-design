pipeline {
    agent any

    options {
        timestamps()
    }

    stages {

        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }

        stage('Test') {
            steps {
                echo "Running unit and integration tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }

    }

    post {
        success {
            echo "Pipeline executed successfully!"
        }
        failure {
            echo "Pipeline failed. Please check logs."
        }
    }
}
