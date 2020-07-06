node{
   stage('SCM Checkout'){
   git 'https://github.com/thanhphamnl/jenkinsdemo'
   }
   
   stage('Clean'){
   bat 'mvn clean'
   
   }
   stage('Install'){
   bat 'mvn package'
   
   }
}
