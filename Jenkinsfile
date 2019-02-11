        node{
    stage('Build and Test'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
        checkout scm
    }

        stage('Example') {
          buid 'job2'               
          echo 'F***'        
        }

}
