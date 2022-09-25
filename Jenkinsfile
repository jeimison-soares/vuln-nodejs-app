// 1. Adicione um SCA a pipeline abaixo
// 2. Não permita que o build falhe mesmo que vulnerabilidades sejam encontradas
// 3. Guarde os resultados em um artefato
// 4. Adicione um dast ao link -> http://testphp.vulnweb.com/

pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
         sh 'npm install'
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
