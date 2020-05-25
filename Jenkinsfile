pipeline {
      agent any 
            stages{
                  stage('build'){
                        steps{
                              echo 'Running build'
                              sh './gradelw build --no-daaemon'
                              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
                        }
                  }
            }
     
}

