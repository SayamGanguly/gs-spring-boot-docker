pipeline {
  agent any
  stages{
    
    stage("Remove"){
      steps{
        sh "rm -rf gs-spring-boot-docker"
      }
    }
          
    stage("Clone Repository"){
      steps{
        sh 'git clone https://github.com/SayamGanguly/gs-spring-boot-docker.git'
      }
    }
    
    stage("Show content"){
      steps{
        sh 'ls -lrt'
      }
    }
    
    stage("Build jar"){
      steps{
        sh 'ls -lrt gs-spring-boot-docker/complete'
      }
    }
  }
}
