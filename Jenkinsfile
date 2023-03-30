pipeline {
    agent any

    stages {
        stage('pull code from github') {
            steps {
                echo 'pull code from github - SUCCESS'
            }
        }
        stage('build docker image') {
            steps {
                echo 'build docker image - SUCCESS'
            }
        }
        stage('sonarqube scan code') {
            steps {
                echo 'sonarqube scan code - SUCCESS'
            }
        }
        stage('push code to server ') {
            steps {
                echo 'push code to server - SUCCESS'
            }
        }
        stage('send message to channel ') {
            steps {
                echo 'send message to channel - SUCCESS'
            }
        }
    }
}
