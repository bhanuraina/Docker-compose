node {
 
    stage 'Checkout'
        checkout scm
        stage 'Integration Test'
        sh "/usr/local/bin/docker-compose -f docker-compose.yml up --force-recreate --abort-on-container-exit"
        sh "/usr/local/bin/docker-compose -f docker-compose.yml down -v"
}
