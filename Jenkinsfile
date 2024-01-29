opipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Test environment'
            }
        }
        stage('Test'){
            steps {
                echo 'UAT environment'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'make publish'
            }
        }
    }
}
