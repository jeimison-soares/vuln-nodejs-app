// 1. Adicione um SCA a pipeline abaixo
// 2. Guarde os resultados em um artefato
// 3. Adicione um dast ao link -> http://testphp.vulnweb.com/

pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
         sh 'npm install'
        }
    }
    stage ('NPM audit') {
      steps {
        sh 'npm audit --json'
      }
    }
    stage('test') {
        steps {
          sh 'echo "Testing"'
        }
    }
    stage('deploy') {
        steps {
          sh 'echo "deploying"'
        }
      }
    }
  }
