pipeline {
    agent any
    stages {
        stage("build") {
            steps {
            echo " This is the buld statge"
            }
        }
        stage("test") {
            steps {
              echo "We are are the testing stage"  
            }
        }
        stage("qa") {
            steps {
              echo " This is quality assurance test"  
            }
        }
        stage("deploy") {
            steps {
              echo "Deploying artifacts to nexus server"  
            }
        }
    }
}
