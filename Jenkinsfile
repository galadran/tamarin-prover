pipeline { 
    agent any
    stages {
        stage('Build') { 
            steps { 
                sh 'make install'
            }
        }
        stage('Test'){
            steps {
                sh 'tamarin-prover test'
            }
        }
    }
}   

