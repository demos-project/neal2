
pipeline {
    agent any
    triggers {
        upstream 'job2'
    }
    stages{
        node{
    stage('Build and Test'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
        checkout scm
    }
}
        stage('Example') {
            steps{
                
                echo 'F***'
        }
        }
}
}
