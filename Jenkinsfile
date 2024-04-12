pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'checking-out at production branch'
            }
        }
        stage('test') {
            steps {
                echo 'running the test at production branch'
            }
        }
        stage('build') {
            steps {
                echo 'building the code at production branch'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying from production branch'
            }
        }
    }
}
