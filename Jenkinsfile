pipeline {
    agent any
 
    stages {
    stage ('preparation')
    { steps
    {tool name:'Maven3',type:'maven'
    }
    }
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

