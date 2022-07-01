pipeline {
  agent any
    
  tools {nodejs "nodejs"}
    
  stages {
        
    stage('Git') {
      steps {
      
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
