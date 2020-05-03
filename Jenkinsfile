Pipeline {
  agent any
  stages{
    stage ('Build'){
      steps{
        echo 'Build In Progress'
        sh './gradelw build --no-deamon
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
      }
    }
  }
}
