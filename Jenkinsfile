pipeline {
    agent any 
    stages {
      stage('install') { 
            steps {
                bat 'cd test'
                bat 'npm install'
            }
        }
        stage('Build') { 
            steps {
                bat 'npm build'
            }
        }
    }
}
