pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo "Building..${env.BUILD_ID} on ${env.JENKINS_URL}"
                mail to: sunil.bhaker@gmail.com, subject: 'The Pipeline succeed :)'
            }
        }
        stage("Test") {
            steps {
                echo "Testing.."
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploying...."
            }
        }
    }
}