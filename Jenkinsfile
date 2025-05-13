pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'python -m tests/test_add.py'
            }
        }
    }
}
