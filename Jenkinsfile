pipeline{
  agent any
  stages{
    stage('build'){
      steps{        
        echo "build is running"
        sh './gradlew build --no-daemon'
        archeiveArtifacts artifacts:'dist/trainSchedule.zip'     
      }
    }
  }
  
}
