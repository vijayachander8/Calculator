def mvnHome= tool name: 'Maven3', type: 'maven'
pipeline {
      agent any

      stages{
      stage('package') {
      steps
      {
                         sh "${mvnHome}/bin/mvn package"
            }
       }
       }
    }


