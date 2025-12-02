pipeline {
    agent any
    stages {
        stage('Run Python Program') {
            steps {
                echo "Running Python Program..."
                bat 'py hello.py'
            }
        }
    }
    post {
        always {
            echo "Python Pipeline Completed."
        }
    }
}
