node {
  stage('Checkout'){
    checkout scm
  }
  stage('Build'){
    sh 'chmod +x helloworld2.sh'
  }
  stage('Test'){
    sh 'cat helloworld2.sh'
  }
  stage('Deploy'){
    sh './helloworld2.sh'
  }
}
