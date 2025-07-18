pipeline {
    agent{
        label "jenkins-slave1"
    }
    stages {
        stage ("Build") {
            steps{
                timeout (time:5, unit:'SECONDS')
                echo "printing timeout pipeline"
                sleep 60
            }
        }
    }
}
