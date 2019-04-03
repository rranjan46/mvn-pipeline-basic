node{
   stage('SCM Checkout'){
     git 'https://github.com/rranjan46/mvn-pipeline-basic'
   }
   stage('Compile-Package'){
       
      sh "mvn package"
   
   }
}
