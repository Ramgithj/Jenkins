
pipeline{
  agent any
  stages{
    stage("create a file") {
      steps {
        sh 'vim aFile'
        sh '"Hello this is a file"'
      }
    }
    stage ("Print the file") {
      steps {
        sh 'cat aFile'
      }
    }
  }
}
