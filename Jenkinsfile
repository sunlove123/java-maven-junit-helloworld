env.dockerimagename="buildon/buildon:v2"
node {
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub - repository
      checkout scm
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
   }
   stage('Build') {
      // Run the maven build
      sh 'mvn clean package -Dmaven.test.failure.ignore=true'
      archive ''
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
