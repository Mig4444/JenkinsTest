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
        gcc main.c -o main
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
