pipeline {
  agent any
  stages {
    stage("welcome to dvs") {
      steps {
        script {
          println "hi Team welcome to Dvs Devops"
          # user defined variables
          var1 = 20 
          println "My var1 value is ${var1}"
          # Predefined variables 
          println "my BUILD_NUMBER is ${BUILD_NUMBER}"
          println "my JOB_NAME is ${JOB_NAME}"
          
        }
      }
    }
  }
}
