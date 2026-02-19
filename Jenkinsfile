pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'git@github.com:chethan14049/maven-clock-app.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}
