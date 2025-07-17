pipeline {
    agent any
    stages{
        stage ("Build"){
            steps{
                echo "coming from the github"
            }
        }
        stage ("groovy stage"){
            steps{
                script{
                    def course = "k8s"
                    println("Thanks for enrolling ${course} course")
                }
            }
        }
    }
}
