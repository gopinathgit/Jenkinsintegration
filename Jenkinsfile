pipeline {
agent any 
stages{
  stage('One') {
      steps{
      echo 'Hi, this is test jenkins'
      }
  }
  stage ('Two') {
      steps {
      input ('Do you want to proceed')
      }
  }
  stage ('Three') {
   steps{
        echo "Hello"
        }
    }
  }
 }
