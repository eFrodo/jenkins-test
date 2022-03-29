pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                echo "Hello"
                sh 'python hello_world.py'
            }
        }
    }
}
