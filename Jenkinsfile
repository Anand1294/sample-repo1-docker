pipeline {
    agent {
      dockerfile true
    }
    stages {
        stage ('Groovy Version Check') {
            steps {
                sh 'groovysh --version'
            }
        }
    }
}
