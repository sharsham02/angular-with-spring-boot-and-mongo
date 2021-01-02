pipeline{
agent any
stages{
stage('build'){
steps {
 sh  "mvn install -DskipTests"
sh "mvn clean install"

 }
}
}

