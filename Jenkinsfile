node {
   stage'edit' 
   checkout scm
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/sunlove123/java-maven-junit-helloworld.git'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
   }
   stage('Build') {
      // Run the maven build
         sh 'mvn clean package -DskipTests=True'
   }
   stage('Results') {
      sh 'echo HelloWorld'
   }
   stage('Results1') {
      sh 'echo HelloWorld'
   }
   stage('Results2') {
      sh 'echo HelloWorld'
   }
   stage('Results3') {
      sh 'echo HelloWorld'
   }
   stage('Results4') {
      sh 'echo HelloWorld'
   }
   stage('Results') {
      sh 'echo HelloWorld'
   }
}
