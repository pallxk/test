pipeline {
    agent any

    stages {
        stage("check [ci skip]") {
            steps {
                scmSkip(deleteBuild: false, skipPattern:'\\[ci skip]|\\[skip ci]')
            }
        }

        stage("test") {
            steps {
                sh "export"
            }
        }
    }
}
