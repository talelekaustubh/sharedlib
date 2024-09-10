pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clones the repository from GitHub
                git 'https://github.com/talelekaustubh/io.git'
            }
        }
        
        stage('Run Hello World') {
            steps {
                // Print a message to indicate the start
                echo 'Running the Hello World Python script...'
                
                // Run the Python script
                sh 'python3 world.py'
            }
        }
    }
}