pipeline{
  agent any
  stages{
    stage('compile'){
      bat '''javac Hello.java'''
    }
    stage('deploy'){
      bat '''java Hello'''
    }
  }
}
