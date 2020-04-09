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
                mvn clean 
                mvn install
                
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
