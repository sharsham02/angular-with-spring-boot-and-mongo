pipeline{
agent any
stages{
stage('build'){
steps {
echo ' automating tool'
sh 'mvn clean package'
archiveArtifacts artifacts: 'dist/angular.jar'
  }
 }
}
}

