node {
   stage('clone Repo') { 
      
   }
   stage('Build') {
      
   }
   stage('Results') {
      junit '**/target/surefire-reports/TEST-*.xml'
      archive 'target/*.jar'
   }
}
