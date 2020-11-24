node
{
    
    stage('CheckoutCOde')
    {
      git credentialsId: 'ea0f21ea-4c9a-411f-8f31-49f825993d6c', url: 'https://github.com/bharnaya/angulalr-node-js.git'  
        
    }
    
    stage('Build')
    {
        
     nodejs(nodeJSInstallationName: 'nodejs'){
         sh "npm install"  
     } 
    }
    
    /*
    stage('ExecuteSonarQubeReport')
    {
        
     nodejs(nodeJSInstallationName: 'nodejs'){
         sh "npm run sonar"  
     } 
    }
    
    stage('RunNodeJsApp')
    {
        
     nodejs(nodeJSInstallationName: 'nodejs'){
         sh "npm start &"  
     } 
    }
    */
}
