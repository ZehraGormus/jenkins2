pipeline {
    agent any

    stages {
        stage('Commit') {
            steps {
                echo 'Code committed'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the Code...'
                sh 'javac Hello.java'
                sh 'java Hello'
            }
        }
        stage('Test') {
            steps {
                echo 'Regression tests running...'
                echo 'Regression tests running...'
            }
        }
    }
}
