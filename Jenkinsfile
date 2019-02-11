pipeline {
    agent any
    triggers {
        upstream 'job1'
    }
    stages {
        stage('Example') {
            steps {
                properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
                echo 'F***'
            }
        }
    }
}
