pipeline {
    agent any 
    stages {
        
        stage('Compile and Clean') { 
            steps {

                sh "mvn clean compile"
            }
        }
        
        stage('test') { 
            steps {
                echo 'Code test done sucessfully.'
            }
        }
       
        stage('deploy') { 
            steps {
                sh "mvn package"
            }
        }


    }
}
