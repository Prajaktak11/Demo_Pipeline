pipeline {
    agent none 
    stages {
        agent {
                docker {
                    image 'python:2-alpine' 
                }
            }
        stage('Build') { 
            
            steps {
                echo 'Hello'
            }
        }
    }
}
