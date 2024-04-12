pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'checking-out at testing branch'
            }
        }
        stage('test') {
            steps {
                echo 'running the test at testing branch'
            }
        }
        stage('build') {
            steps {
                echo 'building the code at testing branch'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying from testing branch'
            }
        }
    }
}
