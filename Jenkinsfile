pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        bat '''javac Hello.java'''
      }
    }
    stage('deploy'){
      steps{
        bat '''java Hello'''
      }
    }
  }
}
