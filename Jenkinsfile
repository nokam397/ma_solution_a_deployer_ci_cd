pipeline{
    agent any
    triggers{
        pollSCM '* * * * *'
    }
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