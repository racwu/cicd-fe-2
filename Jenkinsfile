node {
  stage('Build'){
    sh 'chmod +x helloworld.sh'
  }
  stage('Test'){
    sh 'cat helloworld.sh'
  }
  stage('Deploy'){
    sh './helloworld.sh'
  }
}
