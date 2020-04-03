pipeline {
     agent {
        label 'docker-agent'
     }
     
    
     
     stages {
         stage('Unit Test') {
         
	         steps{
	             sh 'echo Running Test'
	             sh 'echo Running Test2'
	         }
         }
         
         stage('Integration test') {
	         steps{
	             sh 'echo Running Integartion Test'
	         }
         }
         stage('Packaging and versioning') {
         
	         steps{
	            sh 'echo Running Verdionig' 
	         }
         }
         
         stage('Deploy') {
         
	         steps{
	             sh 'echo Running Deploying'
	         }
         }
      }
}
