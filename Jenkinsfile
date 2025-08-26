pipeline{
    agent any
        stages{
           stage('build'){
               steps{
                echo "buildin in progress"
                sh "cat index.html"
               }
           }
        stage('deploy'){
            steps{
            echo "deploy to integration in progress"
            }
        }
        }
}