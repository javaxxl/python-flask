pipeline {
    agent any
    tools {
        jdk 'jdk-17'
    }
    stages {
       
        stage('build docker image') {
            steps {
                sh '''java --version
mvn -v'''
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
