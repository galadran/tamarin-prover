pipeline { 
    agent any
    stages {
        stage('Build') { 
            steps { 
                sh 'make'
            }
        }
        stage('Test'){
            steps {
                sh 'tamarin-prover test'
            }
        }
    }
}   

