node {
 environment {
        PATH = "$PATH:/usr/local/bin"
    }
    stage 'Checkout'
        checkout scm
        stage 'Integration Test'
        sh "docker-compose -f docker-compose.yml up --force-recreate --abort-on-container-exit"
        sh "docker-compose -f docker-compose.yml down -v"
}
