pipeline{
  agent {
      label "jenkins-maven"
    }
  stages{
    stage('Checkout') {
            scm checkout
        }

        stage ('Build'){
          sh "./gradlew -Pversion=${version} build"
        }
  }
 

}
