pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }       
    }
    post{
        always{
            echo "SUCCESS"
        }
    }
}