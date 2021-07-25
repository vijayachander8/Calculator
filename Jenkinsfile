pipeline {
      agent any

      stages{
      stage('package') {
      steps
      {
          def mvnHome= tool name:'Maven3', type: 'maven'
                sh "${mvnHome}/bin/mvn package"
            }
       }
       }
    }


