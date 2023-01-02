pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'kodunu kompayl ediyorum'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Kompayl edilen java kodunu çalıştırıyorum'
                sh 'java Hello'
            }
        }
    }
}