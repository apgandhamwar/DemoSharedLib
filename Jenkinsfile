@Library ('github.com/apgandhamwar/DemoSharedLib') _

pipeline {
    agent any
    stages(){
        stage('call library Hello-Args function'){
            steps{
               script{
                   helloArgs('Jenkins!!')
                   helloArgs.goodbyeWorld('Jenkins!!!!')
               }
            }
        }
    }
}
