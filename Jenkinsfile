pipeline { 
    agent any
    stages {
        stage('Build') { 
            steps { 
                sh 'make local'
            }
        }
        stage('Test'){
            steps {
                sh './tamarin-prover test'
            }
        }
    }
}   

