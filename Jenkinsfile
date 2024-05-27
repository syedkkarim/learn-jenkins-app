pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'echo "Hello Hello from Jenkins via shell" '
                sh 'whoami'
                sh 'date'
            }
        }
    }
}