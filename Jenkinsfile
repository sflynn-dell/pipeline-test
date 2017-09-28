pipeline {
    agent any
    stages {
        stage ('Print'){
            script {
                MY_VERSION = readFile 'Version'
            }
            steps {
               sh "echo ${MY_VERSION}"
            }
        }
    }
}
