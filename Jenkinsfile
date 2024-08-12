pipeline {
    agent any // Specify the agent label here

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Cleaning up...'
            }
        }
    }
}
