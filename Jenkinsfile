node {
  stage('Checkout') {
    checkout scm
  }
}

stage('Input') {
  input 'Go ?'
}


node {
  stage('Test') {
    echo "Brunch name is ${env.BRANCH_NAME}"
  }
}
