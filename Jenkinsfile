pipeline {
    agent any

    stages {
        stage('Run PHP Files') {
            steps {
                script {
                    def files = ['home.php'] // List of PHP files to run

                    for (def file in files) {
                        sh "php ${file}"
                    }
                }
            }
        }
    }
}
