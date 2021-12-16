def message="Hello Anand, Welcome to Groovy Container!"
pipeline {
    agent {
      dockerfile true
    }
    stages {
        stage ('Groovy Version Check') {
            steps {
                script {
                    sh 'groovysh --version'
                    sh 'cat /home/README.md'
                    println ("Message from Container : "+message)
                }
            }
        }
    }
}
