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
        sh 'g++ main.c -o main'
        sh './main'
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
