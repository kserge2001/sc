pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep 4
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep 10
            }
        }
        stage('Maven') {
            steps {
                withMaven(maven : 'M2_HOME') {
                    sh 'mvn clean install'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Deployement') {
            steps {
                echo 'Deploying....'
               
                sleep 10
            }
        }
    }
}
