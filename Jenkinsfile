pipeline {
    agent {
        docker { 
          image 'akumariit6/maven-docker-installed-agent:v1'
          args '--user root -v /var/run/docker.sock:/var/run/docker.sock' // mount Docker socket to access the host's Docker daemon }
    }
    stages {
        stage('Checkout') {
            steps {
                sh 'echo passed'
            }
        }
    }
}
}
