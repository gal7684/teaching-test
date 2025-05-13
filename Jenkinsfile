pipeline {
    agent any
    stages {
        stage('tests/test_add.py') {
            steps {
                sh 'python -m pytest'
            }
        }
    }
}
