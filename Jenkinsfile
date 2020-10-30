
pipeline{
  agent any
  stages{
    stage("create a variable") {
      steps {
        sh 'echo "Hello this is a file"'
      }
    }
    stage ("Print the file") {
      steps {
        sh 'cat helloWorld'
      }
    }
  }
}
