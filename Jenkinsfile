pipeline
{
  agent any
  
  stages
  {
    stage("build")
    {
      steps
      {
        sh echo 'Building application'  
        sh echo 'Info request'  
        sh pwd
        sh ls
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
