pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python3 f1.py'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 f2.py'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python3 f3.py'
            }
        }
    }
}
