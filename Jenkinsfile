pipeline {

   agent any
   stages {
   stage ('Build') { 
      steps {
        echo "Building Project"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
   }   
   }
