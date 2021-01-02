pipeline{
agent any
stages{
stage('build'){
steps {
 sh  'mvn install -Dmaven.test.skip=true'
sh 'mvn clean install'
  }
 }
}
}

