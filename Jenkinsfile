pipeline{
   agent any
   stages{
      stage("Deploy to Dev"){
         when{
            branch "develop"
         }
         steps{
             echo "Deploy to Dev Server" 
         }
      }
      stage("Deploy to UAT"){
         when{
            branch "release"
         }
         steps{
             echo "Deploy to UAT Server" 
         }
      }
      stage("Deploy to Prod"){
         when{
            branch "main"
         }
         steps{
             echo "Deploy to Prod Server" 
         }
      }
   }
}
