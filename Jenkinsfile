        node{
    stage('Build and Test'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger']])])
        checkout scm
    }

        stage('Example') {
          build 'job2'               
          echo 'F***'        
        }

}
