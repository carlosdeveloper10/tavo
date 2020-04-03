pipeline {
     agent {
        label 'docker-agent'
     }
     
    
     
     stages {
         stage('Unit Test') {
		 
		 input {
                message "Should we continue?"
                ok "Yes, we should."
                submitter "alice,bob"
                parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
            }
         
	         steps{
	             sh 'echo Running Test'
	             sh 'echo Running Test2'
	         }
         }
         
         stage('Integration test') {
		 when{
				branch 'release/*'
         	}
		 
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
