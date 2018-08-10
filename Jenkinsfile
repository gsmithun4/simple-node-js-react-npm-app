pipeline {
    agent {
        label ''
    }
    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
				bat 'npm start' 
            }
        }
    }
}