pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello Jenkins, running my program from GitHub!'
            }
        }
        stage('Run Command') {
            steps {
                bat 'java -version'
            }
        }
    }
}
