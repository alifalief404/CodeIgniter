pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'develop', url: 'https://github.com/alifalief404/CodeIgniter.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build aplikasi CodeIgniter (simulasi)'
            }
        }

        stage('Test') {
            steps {
                echo 'Menjalankan testing (simulasi)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy ke server (simulasi)'
            }
        }
    }

    post {
        success {
            echo 'Pipeline berhasil dijalankan!'
        }
        failure {
            echo 'Pipeline gagal!'
        }
    }
}
