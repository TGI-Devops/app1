pipeline {
    agent any

    stages {

        stage('Clone Repo') {
            steps {
				        echo "colone repo........."
                  
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
                // Example:
                // mvn clean package
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
