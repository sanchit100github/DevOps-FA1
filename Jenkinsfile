pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'javac HelloWorld.java' // replace with your actual build commands
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'java HelloWorld' // replace with your test commands
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add any deploy steps here, can just echo for demo
            }
        }
    }
}
