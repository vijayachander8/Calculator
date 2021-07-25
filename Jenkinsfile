 node{
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'Maven3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
  
}

