pipeline {
  agent {
    label "jenkins-maven"
 }
  stages{
    stage('Build') {
      steps{
        sh "./gradlew -Pversion=${version} build"
      }
    }
  }
 

}
