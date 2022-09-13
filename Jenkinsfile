pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                changeRequest()
            }
            steps{
               echo "changeRequest() build done"
            }
        }
    }
}
