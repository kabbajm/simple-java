pipeline{

  agent any
  
  stages {
  
    stage('clone'){
      steps{
        sh "rm -rf *"
        sh "git clone https://github.com/kabbajm/simple-java/"        
      }
    }
  
    stage('build'){
      steps{
        sh "cd simple-java && javac Main.java"
      }
    }
  
    stage('run'){
      steps{
        sh "cd simple-java && java Main"
      }
    }
  }

}
