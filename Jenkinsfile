def message="Hello from container"
pipeline {
    agent {
      dockerfile true
    }
    stages {
        stage ('Groovy Version Check') {
            steps {
                script {
                    //groovysh --version
                    //cat /home/README.md
                    println ("Message from Container : "+message)
                }
            }
        }
    }
}
