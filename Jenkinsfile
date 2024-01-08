pipeline {
    agent any

    stages {
        stage('initialiaze') {
            steps {
                sh 'terraform init'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
            }
        }
        stage('package') {
            steps {
                echo 'Hello package'
            }
        }
    }
}
