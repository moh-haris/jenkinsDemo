pipeline {
    agent any

    stages {
        stage('Build Code') {
            steps {
                sh 'python3 prog1.py'
            }
        }

        stage('Test Code') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
