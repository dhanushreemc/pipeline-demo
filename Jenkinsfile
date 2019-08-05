pipeline {
    agent {
       docker {
          image 'busybox'
       }
    }
    
    stages {
        stage("run") {
            steps {
               echo "running on ubuntu agent"
            }
        }
    }
}
