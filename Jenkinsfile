pipeline {
  agent any
  stages {
    stage('Compiled') {
      steps{
        sh 'mvn clean compile'
      }
    }
    
    stage('UnitTest') {
      steps{
        sh 'mvn clean test'
      }
    }
    
     stage('Package') {
      steps{
        sh 'mvn clean package'
      }
    }    
  }
}
