pipeline {
    agent {
        docker {
            image 'alpine'
            args '-v /c/ProgramData/Jenkins/.jenkins/workspace/docker-1/:/workspace -w /workspace'
        }
    }
    stages {
        stage('Hello World') {
            steps {
                sh 'echo Hello World from Alpine container!'
            }
        }
    }
}
