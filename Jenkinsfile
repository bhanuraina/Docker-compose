node {
 dockerCompose {
  executable = '/usr/local/bin/docker-compose'
}
    stage 'Checkout'
 
        checkout scm
        stage 'Integration Test'
   
        sh "docker-compose --version"
        
}
