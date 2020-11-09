pipeline {
  agent any
  stages {'Build'} { 
     steps { 
       echo 'Running build automation'
       sh './gradlew build' --no-daemon'
       archiveArticfacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
