pipeline {
  agent any 
  stages {
    stage('working with loops') {
      steps {
        script {
          for(i=1;i<=5;i++){
            println "my i value is ${i}"
          }
          list_of_subjects = ["devops","azure","aws"]
          for ele in list_of_subjects {
            println "subject name is ${ele}"
          }
          j=10
          while (j<=20){
            println "value of j is ${j}"
            j = j + 1
          }
        }
      }
    }
  }
}
