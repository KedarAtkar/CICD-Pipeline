pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('GitCheckout') {
            steps {
                sh 'echo "Mid"'
            }
        }
        stage('end') {
            steps {
                sh 'echo "end"'
            }
        }
    }
}