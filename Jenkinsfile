pipeline {
  agent { docker { image 'maven:3.8.6-openjdk-11-slim' } }
  stages{
    stage("Clone Repository"){
      steps{
        sh 'git clone https://github.com/SayamGanguly/gs-spring-boot-docker.git'
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
