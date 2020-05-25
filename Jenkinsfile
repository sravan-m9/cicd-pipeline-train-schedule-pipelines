pipeline {

      stages {
         stage ('Build') {
        steps {
        echo 'Running Build'
        sh './gradelw build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
      }

}
