pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello world'
            }
        }
    }
    post {
        always {
            echo "sending email"
        }
    }
}