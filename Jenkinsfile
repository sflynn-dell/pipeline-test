pipeline {
    agent {
       label 'Test'   
    }
    environment {
        MY_VERSION = readFile 'Version'
    }
    stages {
        stage ('Print'){
            steps {
               sh "echo ${MY_VERSION}"
            }
        }
    }
}
