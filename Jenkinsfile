pipeline {

    agent { node { label 'TB_L' } }
    stages {

        stage('Build') {

            steps {

                sh 'hostname'

            }

        }

        stage('Test') {

            steps {

                sh 'ifconfig'

            }

        }

        stage('Deploy') {

            steps {

                echo 'Deploying Example'

            }

        }

    }

}
