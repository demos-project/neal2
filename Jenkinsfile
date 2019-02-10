node{
  stage('FIRST-JOB'){
    git 'https://github.com/demos-project/neal2.git'
  }
  stage('Second-Job'){
  triggers {
  upstream 'pipeline, First-job, '
}
  }
}
