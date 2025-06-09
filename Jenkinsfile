pipeline {
    agent { 
        label 'label'
    }
    stages {
        stage('Server host') {
            steps {
                sh 'hostname'
            }
        }
        stage('Server uptime') {
            steps {
                sh 'uptime'
            }
        }
        stage('Server disk usage') {
            steps {
                sh 'df -h'
            }
        } 
        stage('cpu details') {
            steps {
                sh 'lscpu'
            }
        }
        stage('memory usage') {
            steps {
                sh 'free -h'
            }
        }
        stage('Date') {
            steps {
                sh 'date'
            }
        } 
    }
}
