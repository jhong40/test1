pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M398"
    }

    stages {
        stage("Echo Version") {
            steps {
               // git 'https://github.com/jhong40/test1.git'
                sh 'echo maven version'
                sh 'mvn --version'

            }
        }
    }
}
