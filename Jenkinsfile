pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/SiyahEylem/JenkinsDemo.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean package'  // Windows için

            }
        }
    }
}