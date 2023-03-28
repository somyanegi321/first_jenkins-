pipeline
{
  agent any
  
    stages{
      stage("clone"){
        steps{
          git credentialsId: 'fl1', url: 'https://github.com/somyanegi321/first_jenkins-.git'
        }
        
        
      }
      stage("build){
        steps{
          sh 'python first.py'
        }
        
        
      
    }
  }
}
      
