pipeline {
    agent any

    stages {
        stage('Run PHP Files') {
            steps {
                script {
                    def files = ['save_data.php'] // List of PHP files to run

                    for (def file in files) {
                        sh "php ${file}"
                    }
                }
            }
        }
    }
}
