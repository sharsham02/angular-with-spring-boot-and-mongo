pipeline{
agent any
stages{
stage('build'){
steps {
sh 'mvn clean install'
archiveArtifacts artifacts: 'dist/angular.jar'
  }
 }
}
}

