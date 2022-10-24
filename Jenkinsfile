pipeline {
    agent any

    stages {
        stage('1st Stage') {
            steps {
                sh './src/10_date.sh'
            }
        }
        stage('2nd Stage') {
            steps {
                sh './src/20_disk.sh'
            }
        }
        stage('3rd Stage') {
            steps {
                sh './src/30_hostname.sh'
            }
        }
    }
}
