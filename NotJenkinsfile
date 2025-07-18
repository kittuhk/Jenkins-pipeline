pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages{
        stage ('Build'){
            steps{
                 echo "print mvn version"
                 sh "mvn --version"
            }   
        }
        stage ("Sonar"){
            steps{
                echo "print sonar"
            }
        }
        stage ('Docker'){
            steps{
                echo "print Docker"
            }
        }
    }
}
