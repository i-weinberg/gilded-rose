pipeline {
    agent none 
    stages {
        stage('Unit-Testing') {
            agent { docker 'python:2.7-alpine3.7' }    
            steps {
                sh "python python/test_gilded_rose.py"
            }
        }
        stage('artifact') {
            agent any
            steps {
                echo 'saving artifacts'
            }
        }
    }
}
