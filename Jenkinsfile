pipeline {
    agent { dockerfile {dir 'nginx/Dockerfile'} }
    stages {
        stage('Test') {
            steps {
                echo 'Hello world!'
            }
        }
    }
}
