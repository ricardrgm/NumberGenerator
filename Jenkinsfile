#!groovy
pipeline {
    agent any
    
    tools { 
        maven 'Maven 3.6.0' 
        jdk 'jdk8' 
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
