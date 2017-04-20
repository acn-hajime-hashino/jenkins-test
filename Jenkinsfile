parameters {
    string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
}

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
