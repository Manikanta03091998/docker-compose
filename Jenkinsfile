pipeline{
    agent any
    stages{
        stage("maven build"){
            steps{
            sh 'mvn clean package'
            }
        }
          stage('To show data') {
            steps {
                echo "I'm a Bad guy"
            }
        }
    }
}
