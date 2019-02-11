node {

    triggers {
        upstream 'job1'
    }

        stage('Example') {

                properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
                echo 'F***'
        }
    
}
