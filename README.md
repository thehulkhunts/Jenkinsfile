# Jenkinsfile
pipeline{
agent{label "label11"}
stages{
  stage ("build"){
       steps{
            echo " this is building ...."
            }
            }
            stage("test") {
            steps{
                 echo"this is testing ..."
                 }
                 }
           }
           }
           
