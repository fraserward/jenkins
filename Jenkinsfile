node{
  stage('SCM Checkout') {
    git 'https://github.com/fraserward/jenkins'
  }
  Stage('Comple-Package'){
    sh 'mvn package'
  }
}
