pipeline {
  agent any
  parameters {
    choice choices: ['dev', 'sit', 'uat'], description: 'select the environment', name: 'ENV'
    string defaultValue: '0.0.0', description: 'provide the version number', name: 'VERSION', trim: true
  }  
  stages {
    stage("welcome to dvs") {
      steps {
        script {
          println "hi Team welcome to Dvs Devops"
          // user defined variables
          var1 = 20 
          println "My var1 value is ${var1}"
          // Predefined variables 
          println "my BUILD_NUMBER is ${BUILD_NUMBER}"
          println "my JOB_NAME is ${JOB_NAME}"
          // Accessing values of parameters
          println "my selected env is ${params.ENV}"
          println "my selected version is ${params.VERSION}"
        }
      }
    }
  }
}
