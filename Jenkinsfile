pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Compiling Java Program..."
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo "Running Java Program..."
                bat 'java HelloWorld'
            }
        }
    }
    post {
        always {
            echo "Java Pipeline Completed."
        }
    }
}
