pipeline {
  agent {
    docker {
      image '3.5.4-jdk-10:latest'
    }

  }
  stages {
    stage('Build') {
      agent {
        docker {
          image '3.5.4-jdk-10'
        }

      }
      steps {
        sh 'mvn -f spring-boot-samples/spring-boot-sample-atmosphere/pom.xml'
      }
    }
  }
}