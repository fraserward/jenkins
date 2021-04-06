node{
  stage('SCM Checkout') {
    git 'https://github.com/javahometech/my-app'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
  stage('EMail Notification'){
    mail bcc: '', body: 'THis is a test', cc: '', from: '', replyTo: '', subject: 'Test', to: 'Me' }
}
