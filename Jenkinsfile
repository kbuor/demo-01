pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo "Building code..."
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
            }
        }
    }
}
