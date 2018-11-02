pipeline {
  agent any
  stages {
    stage('commit_stage') {
      steps {
        sh 'echo "fase de commit stage"'
      }
    }
    stage('staging') {
      steps {
        sh 'echo "staging"'
      }
    }
    stage('producao') {
      steps {
        sh 'echo "producao"'
      }
    }
  }
}