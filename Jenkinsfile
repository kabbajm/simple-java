pipeline{

  agent any
  
  stages {
  
    stage('clone'){
      step{
        sh "rm -rf *"
        sh "git clone https://github.com/kabbajm/simple-java/"        
      }
    }
  
    stage('build'){
      step{
        sh "cd simple-java && javac Programme.java"
      }
    }
  
    stage('run'){
      step{
        sh "cd simple-java && javac Programme.java"
      }
    }
  }

}
