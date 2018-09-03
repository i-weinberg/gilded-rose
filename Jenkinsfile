pipeline {
    agent none 
    stages {
        stage('Unit-Testing') {
            agent any  
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
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
