pipeline {
  agent any

  stages {
  
    stage('Push Artifact to S3') {
      steps {
        sh 'aws s3 cp . s3://demo-siva/demo/ --recursive --exclude "Jenkinsfile"'
      }
    }

}
}
