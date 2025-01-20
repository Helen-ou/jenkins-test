pipeline {
  agent any
  tools {
    maven 'Maven-Test'
  }
  
  
  stages {
    stage("build") {
      steps {
        echo 'Building the application'
        sh 'mvn -v'
      }
    }
    stage("test") {
      steps {
        echo 'Testing the application'
      }
    }
    stage("deploy") {
      steps {
        echo 'Deploying the application'
      }
    }
  }
}
