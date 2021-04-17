#!groovy

pipeline {
    agent any
    stages {
        stage('Build container') {
            steps {
                sh "docker image build"
            }
        }
        stage('Test') {
            steps {
                echo "pidor2"
            }
        }
        stage('Deploy')
            steps {
                echo "pidor3"
        }
    }
}
