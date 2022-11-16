pipeline
{
  agent any
  
  stages
  {
    stage("build")
    {
      steps
      {
        echo 'Building application'  
        echo 'Info request'  
        pwd
        ls
        echo 'Info answers'  
      }
    }
    stage("test")
    {
      steps
      {
        echo 'Testing application'        
      }
    }
    stage("deploy")
    {
      steps
      {
        echo 'Deploying application'        
      }
    }    
  }
}
