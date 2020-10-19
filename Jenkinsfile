pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './gradlew clean compileJava'
      }
    }

    stage('Test') {
      steps {
        sh './gradlew test'
      }
    }

    stage('Validate') {
      steps {
        echo 'Aca realizamos las validaciones!'
      }
    }

    stage('Deploy') {
      steps {
        echo 'En esta etapa hacemos deploy.'
      }
    }

  }
}