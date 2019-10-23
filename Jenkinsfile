node{
  stage('SCM Checkout'){
  
    git 'https://github.com/Harishmh/maven-quick-start.git'
    
    }
 stage('Compilr package'){
    
     sh label: '', script: 'mvn clean package'
        
    }
  stage('Email Notification'){
    
     mail bcc: 'C.Harish@thomsonreuters.com', body: '''Build successful

      Thanks!!
      Harish
      9553175531''', cc: 'c.harish', from: '', replyTo: '', subject: 'build successful', to: 'c.harish@hotmail.com'    
    }
    
}
