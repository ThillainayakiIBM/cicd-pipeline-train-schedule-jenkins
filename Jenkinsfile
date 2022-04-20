pipeline{
  agent any
  stages{
    stage('build'){
      steps{        
        echo "build is running"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'     
      }
    }
  }
  
}
