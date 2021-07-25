pipeline {
    agent any
  
tool name:'Maven3',type:'maven'   
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

