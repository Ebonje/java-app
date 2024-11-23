pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'cloning source code from git hub'
            }
        }
        stage('Test') {
            steps {
                echo 'testing application code for bugs and code smells'
            }
        }
        stage('BuildJar') {
            steps {
                echo 'build artifact from soure code'
            }
        }
        stage('Deploy to nexus') {
            steps {
                echo 'Deploying artifact to nexus'
            }
        }
        stage('BuildImage') {
            steps {
                echo 'building docker image '
            }
        }
    }
}
