node{
  stage('SCM Checkout'){
  
    git 'https://github.com/Harishmh/maven-quick-start.git'
    
    }
 stage('Compilr package'){
    
     sh label: '', script: 'mvn clean package'
        
    }
  
    
}
