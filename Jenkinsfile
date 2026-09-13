@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        stage('Test,sonartest,code scan,docker build') {
            steps {
                checkoutAndTest()
            }
        }
    }
}
