pipeline{
  agent any
  stages{
    stage('build'){
      echo "build is running"
      sh './gradlew build --no-deomon'
      archeiveArtifacts artifact:'dist/trainSchedule.zip'      
    }
  }
  
}
