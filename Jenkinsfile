pipeline {
    agent any
    
    stages {
        stage (checkout scm){
            steps {
            checkout scm
            }
        }
        stage ("test") {
            steps {
             sh "./exec-jmeter.sh 3"

            }
             

        }
    
    }

}
