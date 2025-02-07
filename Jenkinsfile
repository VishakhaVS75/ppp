pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Sample.java'
		
            }
        }
        stage('Run') {
            steps {
                bat 'java Sample'
            } 
        }
    }
}
