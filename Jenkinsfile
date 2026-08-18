pipeline {

    agent none

    stages {

        stage('Build') {



            steps {
                echo '=============================='
                echo 'BUILD STAGE'
                echo '=============================='
                echo 'Build agent is working'
            }
        }

        stage('Test') {


            steps {
                echo '=============================='
                echo 'TEST STAGE'
                echo '=============================='
                echo 'Test completed successfully'
            }
        }

        stage('Deploy') {

            steps {
                echo '=============================='
                echo 'DEPLOY STAGE'
                echo '=============================='
                echo 'Deploy agent is working'
                echo 'Website deployment completed'
            }
        }
    }

    post {
        success {
            echo '=============================='
            echo 'PIPELINE SUCCESS'
            echo '=============================='
        }

        failure {
            echo '=============================='
            echo 'PIPELINE FAILED'
            echo '=============================='
        }
    }
}
