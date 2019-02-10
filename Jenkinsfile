pipeline {
    agent any
    triggers {
        upstream 'firstjob, First-job, '
    }
    stages {
      stage('FIRST-JOB'){
        steps{
    git 'https://github.com/demos-project/neal2.git'
        }
  }
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
