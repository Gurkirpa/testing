pipeline {
    agent any // Use any available agent
    
    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                // Run the build command (replace with your build tool, e.g., Maven, Gradle, npm)
                sh 'echo Building the project...'
            }
        }
        
        stage('Test') {
            steps {
                // Run tests (replace with your test command)
                sh 'echo Running tests...'
            }
        }
        
        stage('Deploy') {
            steps {
                // Deploy the application (add deployment steps here)
                sh 'echo Deploying the application...'
            }
        }
    }
    
    post {
        always {
            // Clean up workspace or send notifications
            echo 'Pipeline finished!'
        }
    }
}
