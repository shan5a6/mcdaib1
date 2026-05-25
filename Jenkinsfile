def myfn(){
  println "welcome  to jenkins functions"
}
def subject_details(subject){
  println "subjected passed is ${subject}"
}
pipeline {
  agent any 
  stages {
    stage('working with functions') {
      steps {
        script {
          myfn()
          subject_details("devops-with-ai")
        }
      }
    }
  }
}
