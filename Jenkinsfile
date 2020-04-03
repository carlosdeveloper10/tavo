pipeline {
     agent {
        label 'docker-agent'
     }
     
     environment {
         
     }
     
     stages {
         stage('Unit Test') {
         
	         step{
	             sh 'echo Running Test'
	             sh 'echo Running Test2'
	         }
         }
         
         stage('Integration test') {
	         step{
	             sh 'echo Running Integartion Test'
	         }
         }
         stage('Packaging and versioning') {
         
	         step{
	            sh 'echo Running Verdionig' 
	         }
         }
         
         stage('Deploy') {
         
	         step{
	             sh 'echo Running Deploying'
	         }
         }
      }
}
