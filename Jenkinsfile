pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Compiling Java Program..."
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo "Running Java Program..."
                sh 'java HelloWorld'
            }
        }
    }
    post {
        always {
            echo "Java Pipeline Completed."
        }
    }
}
