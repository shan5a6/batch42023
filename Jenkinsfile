def myfn1(a,b) {
  println "value of a is ${a},value of b is ${b}"
}


pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          myfn1(10,20)
        }
      }
    }
  }
}
