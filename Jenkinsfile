pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo "Building code..." >> demo01.txt
            }
        }
        stage('Test') {
            steps {
                echo "Testing..." >> demo01.txt
            }
        }
    }
}
