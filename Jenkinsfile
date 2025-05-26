pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        echo 'Build Sucessfully'
      }
    }
    stage('Run'){
      steps{
        echo 'Run Sucessfully'
        bat 'node index.js'
      }
    }
  }
}
