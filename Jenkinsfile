pipeline {
 agent {
    node { label 'workstation' }
 }

   stages {

        stage ('test') {
          steps {
            sh 'echo test'

          }
        }
        stage ('Code analysis') {
          steps {
            sh 'echo Code analysis'

          }
        }
        stage ('Security scans') {
          steps {
            sh 'echo Security scans'

          }
        }
        stage ('Publish an artifactory') {
          steps {
            sh 'echo Publish an artifactory'

          }
        }
   }
}