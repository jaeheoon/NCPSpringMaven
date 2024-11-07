pipeline {
    agent any
    stages {
        stage('111') {
            steps {
                echo '1번 stage 실행'
                // Git checkout 명령어
            }
            steps {
                echo '1-1번 stage 실행'
                // Git checkout 명령어
            }
        }
        stage('222') {
            steps {
                echo '2번 stage 실행'
                // Maven 빌드 명령어
            }
        }
        stage('333') {
            steps {
                echo '3번 stage 실행'
                // 테스트 실행 명령어
            }
        }
    }
}
