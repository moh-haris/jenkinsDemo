pipeline {
    agent any

    stages {

        stage('Clone Git') {
            steps {
                git 'https://github.com/your-username/Jenkins-Demo.git'
            }
        }

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
