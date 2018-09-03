pipeline {
    agent none 
    stages {
        stage('Unit-Testing') {
            agent any  
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
