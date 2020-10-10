node {
 checkout scm
 docker.withRegistry('https://registry.hub.docker.com','prembudda'){
  
   def customImage = docker.build("miltomc/dockerwebapp")
    customImage.push()
     }
 }
