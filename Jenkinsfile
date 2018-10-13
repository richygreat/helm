pipeline {
  agent any
  stages {
    stage('Kubernetes Check') {
      steps {
        sh "kubectl config view"
      }
    }
    stage('Helm Check') {
      steps {
        sh "helm version"
      }
    }
  }
}
