#!/usr/bin/env 

pipeline {
    agent any 
    stages {
        stage('Pull Code') {
            steps {
                echo 'Pulling code!'
                sh 'python -m py_compile Hello.py'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Code!' 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Code!' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Code!' 
            }
        }
    }
}
