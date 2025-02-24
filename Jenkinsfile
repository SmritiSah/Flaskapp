pipeline {
    agent {
        docker { image 'alpine' }
    }

    stages {
        stage('Hello from Docker') {
            steps {
                sh 'echo "Hello, World from Docker!"'
            }
        }
    }
}

