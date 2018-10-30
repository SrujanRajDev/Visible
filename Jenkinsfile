node {
   stage('clone Repo') { 
      bat 'git clone https://github.com/SrujanRajDev/Visible.git
   }
   stage('Build') {
      bat 'mvn compile'
   }
   stage('Test') {
      bat 'mvn test'
   }
   stage('Package') {
      bat 'mvn package'
   }
}
