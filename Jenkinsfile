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
        stage('Hello1'){
            steps {
                echo 'Hello world'
            }
        }
        stage('Hello2'){
            steps{
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