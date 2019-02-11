        node{
    stage('Build and Test'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
        checkout scm
    }

        stage('Example') {
          build 'job2'               
          echo 'F***'        
        }

}
