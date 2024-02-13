pipeline{
    agent any
    stages{
        stage("maven build"){
            steps{
            sh 'mvn clean package'
            }
        }
    }
    stages {
        stage('Hello') {
            steps {
                echo "I'm a Bad guy"
            }
        }
    }
}
