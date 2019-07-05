pipeline {
    agent { dockerfile {dir 'nginx'} }
    stages {
        stage('Test') {
            steps {
                echo 'Hello world!'
            }
        }
    }
}
