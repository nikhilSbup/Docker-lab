pipeline {
    agent any
    parameters {
        string(name:'NAME', defaultValue:'', description: 'Enter your name')
    }
    stages {
        stage('Good Morning!!') {
            steps {
                echo "Hello, ${params.NAME}!!"
            }
        }
    }
}
