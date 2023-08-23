pipeine {
    agent any
    stages{
        stage('Source'){
            //get code from a Github repository
            git 'https://github.com/Nav9n/angular-admin.git'
            //Run npm install to install node modules
            sh "npm install"
            echo 'Source Stage Finished'
        }
    }
}