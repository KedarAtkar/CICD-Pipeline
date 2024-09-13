pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('GitCheckout') {
            steps {
                sh 'echo "Mid"'
                print "Hello"
            }
        }
        stage('end') {
            steps {
                sh 'echo "end"'
                println "HI"
            }
        }
    }
}