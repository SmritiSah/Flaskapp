pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    docker.image('node:22.14.0-alpine3.21').inside("-w /mnt/c/ProgramData/Jenkins/.jenkins/workspace/docker-1/") {
                        sh 'echo Running inside Docker'
                    }
                }
            }
        }
    }
}
