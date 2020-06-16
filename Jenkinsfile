#!/usr/bin/env 

pipeline {
    agent none 
    stages {
        stage('Build') { 
            steps {
                echo 'Hello'
                sh 'python -m py_compile Hello.py' 
                
            }
        }
    }
}
