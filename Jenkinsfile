pipeline
{
  agent any
    stages{
      stage("clone"){
        steps{
           git branch: '', credentialsId: 'b3f67285-ed4b-4258-92e5-4d7ca293b5da', url: 'https://github.com/somyanegi321/first_jenkins-.git'
        }
        
        
      }
      stage("build"){
        steps{
          sh 'python first.py'
        }
        
        
      
    }
  }
}
      
