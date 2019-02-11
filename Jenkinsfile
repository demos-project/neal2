node{
    stage('Build and Test'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
    }
}
pipeline {
    agent any
    triggers {
        upstream 'job1'
    }
    stages{
        stage('Example') {
            steps{
                
                echo 'F***'
        }
        }
}
}
