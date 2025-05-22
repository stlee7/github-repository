pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/yourusername/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo '빌드 중...'
            }
        }
        stage('Test') {
            steps {
                echo '테스트 실행 중...'
            }
        }
        stage('Deploy') {
            steps {
                echo '배포 중...'
            }
        }
    }
}
