pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'mvn -f spring-boot-samples/spring-boot-sample-atmosphere/pom.xml clean package'
      }
    }
  }
}