pipeline {
  stages{
    stage("Clone Repository"){
      steps{
        checkout scm
      }
    }
    
    stage("Change Directory") {
      steps{
        sh 'cd gs-spring-boot-docker/complete'
      }
    }
    
    stage("Show content"){
      steps{
        sh 'ls -lrt'
      }
    }
  }
}
