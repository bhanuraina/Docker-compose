node {
 environment {
        PATH = "$PATH:/usr/local/bin"
    }
    stage 'Checkout'
        checkout scm
        stage 'Integration Test'
        sh "docker --version"
        
}
