pipeline {

   agent any
   steps {
    stage ('Build') { 
      steps {
        echo "Building Project"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
   }   
   }
