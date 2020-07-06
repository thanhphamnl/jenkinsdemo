node{
   stage('SCM Checkout'){
   git 'https://github.com/thanhphamnl/jenkinsdemo'
   }
   
   stage('Clean'){
   bat 'mvn clean'   
   }
   
   stage('Test'){
   bat 'mvn test'   
   }
   
   stage('Install'){
   bat 'mvn package'   
   }
}
