pipeline {
  agent {
    label "jenkins-maven"
 }
  stages{
    stage('checkout') {
      steps{
        scm checkout
      }
    }
    stage('Build') {
      steps{
        sh "./gradlew -Pversion=${version} build"
      }
    }
  }
 

}
