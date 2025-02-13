pipeline{
agent any 
  stages {
   stage('build') {
     steps {
       bat 'mvn compile'
     }
  }
    stage('Test') {
    steps{
       bat 'mvn test'
    }
    }
    stage ('Deploy') {
      steps {
        echo 'Application Deployed Successfully'
      }
    }
}
}
