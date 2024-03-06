pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        build 'PES2UG21CS313-1'
        sh 'g++ main.cpp -o outut'

      }
    }
    stage('Test'){
      steps{
      sh './ou'
      }
    }
    stage('Deploy'){
      steps{
        echo 'deploy'
      }
    }
  }
  post{
    failure{
      error 'Pipeline failed'
    }
}
}
