node
{
 
  stage("CheckOutCodeGit")
  {
   git credentialsId: 'gitcredentails', url: 'https://github.com/snbabu453/nodejs-app-mss.git'
 }
 
 stage("Build")
 {
 nodejs(nodeJSInstallationName: 'nodejs15.2.1') {
        sh 'npm install'
    }
 }  
 
 
      
   
	
