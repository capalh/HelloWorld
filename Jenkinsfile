pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '"
            ls -alh
            echo "Multiline shell steps works too"
            "'
      }
    }
  }
}
