pipeline {
  stages{
    stage("Clone Repository"){
      steps{
        checkout scm
      }
    }
    
    stage("Change Directory") {
      sh 'cd gs-spring-boot-docker/complete'
    }
    
    stage("Show content"){
      sh 'ls -lrt'
    }
  }
}
