pipeline {
    agent any
           
    stages
    {
    stage('build') 
        {
    steps {
      echo "Running tests in a fully containerized environment..."
              sh '/usr/local/bin/docker-compose up'
          }
  }
        stage('Deliver')
        {
            steps {
                echo 'Hello'
            }
    }
    }
}
