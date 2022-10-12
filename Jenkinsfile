pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "npm install"
                sh "npm run build" //commentaire
                sh "npm test"
            }
        }
    }
}