node{
   stage('SCM Checkout'){
     git 'https://github.com/eni-pradeep/helloworld.git'
   }
   stage('Compile-Package'){
   def mvnHome = tool name: 'maven-3', type: 'maven'
   sh "${mvnHome}/bin/mvn package"
   }   
}
