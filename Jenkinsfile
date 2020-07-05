node{
   stage('SCM Checkout'){
   git 'https://github.com/thanhphamnl/jenkinsdemo'
   }
   
   stage('Clean'){
   sh 'mvn clean'
   
   }
   stage('Install'){
   sh 'mvn package'
   
   }
}
