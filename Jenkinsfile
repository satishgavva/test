pipeline{

agent any 
  
  stages{
  
    stage ('clone'){
      
      steps {
    
    git url :'' , branch 'main'
        
      }
    
    }
    
    stage('build'){
    
      steps {
      
      sh 'mvn package'
      
      }
    
    
    }
    
    
  
  
  
  }





}
