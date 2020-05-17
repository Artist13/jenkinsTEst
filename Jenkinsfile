pipeline {
  agent { docker { image 'gcc:latest' } }
  stages {
    stage('build') {
      steps {
        sh 'gcc --version'
        sh 'echo "Hello world!"'
        sh '''
            echo "Multiline shell steps works too"
            ls -lah
        '''
      }
    }
  }
}
