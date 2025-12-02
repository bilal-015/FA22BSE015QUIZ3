pipeline {
    agent any
    stages {
        stage('Run Python Program') {
            steps {
                echo "Running Python Program..."
                sh 'python3 hello.py'
            }
        }
    }
    post {
        always {
            echo "Python Pipeline Completed."
        }
    }
}
