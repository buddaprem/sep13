pipeline {
stage('scm') 
 docker.withRegistry('https://registry.hub.docker.com','dockerHub'){
  
   def customImage = docker.build("prembudda/dockerwebapp")
    customImage.push()
     }
 }
