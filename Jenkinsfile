pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          File myfile = new File("/tmp/test.txt")
          println myfile.text
          for(line in myfile.readLines()){
            println "my line is ${line}"
          }

        }
      }
    }
  }
}
