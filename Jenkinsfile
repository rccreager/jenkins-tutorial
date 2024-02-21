pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'echo "Hello World build"'
            }
        }
        stage('test') {
            steps {
                sh 'echo "Hello World test"'
            }
        }
    }
}
