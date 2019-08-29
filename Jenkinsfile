pipeline {
    agent {
        any
          
            }
    stages
    {
    stage('build') 
        {
    steps {
      echo "Running tests in a fully containerized environment..."
              sh './run_tests.sh'
          }
  }
        stage('Deliver') {
            steps {
                echo 'Hello'
            }
    }
}
