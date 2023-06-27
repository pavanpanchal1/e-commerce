
pipeline {
    agent any
    
    stages {
        stage('Run PHP') {
            steps {
                sh 'php index.php'
                sh 'php register.php'
                sh 'save_data.php'
                
            }
        }
    }
}
