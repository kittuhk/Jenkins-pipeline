pipeline {
    agent any 
    stages {
        stage ("Build") {
            steps {
                retry(3){
                    echo "print jenkins pipeline"
                    error "This will give some error"
                }
                echo "retrying multiple times"
            }
        }
    }
}
