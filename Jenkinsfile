pipeline {
    agent any
    stages {
        stage('Source') {
            steps {
                // Fetch code from a GitHub repository
                git url: 'https://github.com/Nav9n/angular-admin.git'
                
                // Run npm install to install node modules
                sh 'npm install'
                
                // Print a message
                echo 'Source Stage Finished'
            }
        }
    }
}
