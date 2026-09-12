pipeline {
    agent any

    stages {

        stage('BUILD') {
            steps {
                echo 'Build started'
                sh 'ls -lrt'
                sh 'hostname'
                sh 'pwd'
                echo 'Build completed'
            }
        }

        stage('TEST') {
            steps {
                echo 'Testing started'
                sh 'echo Running tests'
                sh 'date'
                echo 'Testing completed'
            }
        }

        stage('DEPLOY') {
            steps {
                echo 'Deployment started'
                sh 'echo Deploying application'
                sh 'hostname'
                echo 'Deployment completed'
            }
        }
    }
}
