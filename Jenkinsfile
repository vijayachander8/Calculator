pipeline {
    agent any
    tools {
     

   
    stages {
        stage('Compile') {
            steps { 
                sh 'mvn compile'
            }
        }
       stage('package') {
            steps { 
                sh 'mvn package'
            }
        }
    }
}

