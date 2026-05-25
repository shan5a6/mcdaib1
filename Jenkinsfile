pipeline {
  agent any
  parameters {
  choice choices: ['dev', 'prod'], description: 'select the environment', name: 'ENV'
  } 
  environment {
  JAVA_VERSION = "1.8.10"
  }

  stages {
    stage('working with variables') {
      steps {
        script {
          // declaring userdefined variables
          var1=100
          //accessing  values of a variables 
          println "my variable value is ${var1}"

          // consuming predefined variables
          println "my current execution folder is ${WOKRSPACE}"

          // consuming parameter variables
          println "my selected environment is ${params.ENV}"
          // consuming environment variables
          println "my selected java version is  is ${env.JAVA_VERSION}"          
        }
      }
    }
  }
}
