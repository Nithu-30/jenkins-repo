pipeline {

    agent any

    stages {

        stage('Clone Repository') {

            steps {

                git 'https://github.com/USERNAME/website-project.git'

            }

        }

        stage('Build') {

            steps {

                echo "No Build Required"

            }

        }

        stage('Deploy Website') {

            steps {

                sh '''
                sudo cp -r * /var/www/html/
                '''
            }

        }

    }

}
