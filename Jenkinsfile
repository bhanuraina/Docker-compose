node {
 
    stage 'Checkout'
 
        checkout scm
        stage 'Integration Test'
   withEnv(["PATH=$PATH:~/.local/bin"])
        sh "docker-compose --version"
        
}
