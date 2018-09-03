pipeline {
    agent none 
    stages {
        stage('Unit-Testing') {
            agent { label 'python' }    
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
