pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout Code'
                // Git checkout 명령어
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project'
                // Maven 빌드 명령어
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests'
                // 테스트 실행 명령어
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production'
                // 배포 명령어
            }
        }
    }
}
