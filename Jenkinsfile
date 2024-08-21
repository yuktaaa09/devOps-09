pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'javac hello.java'
            }
            
        }
        stage('Build') {
            steps {
                bat 'java hello'
            }
            
        }
        
    }
}
