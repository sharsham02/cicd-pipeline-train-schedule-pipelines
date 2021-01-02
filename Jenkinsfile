pipeline{
agent any
stages{
stage('build'){
steps{
echo ' Running build automation'
sh './gradlew build --no-dameon'
archiveArtifacts artifacts:'dist/trainschedule.zip'
   }
   }
 }
} 
