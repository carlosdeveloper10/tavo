pipeline {
     agent {
        label 'docker-agent'
     }
     
     stages {
         stage('Unit Test') {
            sh 'echo Running Test'
         }
         
         stage('Integration test') {
            sh 'echo Running Integartion Test'
         }
         
         stage('Packaging and versioning') {
            sh 'echo Running Verdionig'
         }
         
         stage('Deploy') {
            sh 'echo Running Deploying'
         }
     }
}
