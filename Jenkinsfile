// 1. Adicione um SCA a pipeline abaixo
// 2. Guarde os resultados em um artefato
// 3.

pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
         sh 'npm install'
      }
      stage('test')
        steps {
          sh 'echo "Rodando testes de integração"'
        }
      stage('deploy')
        steps {
          sh 'echo "Fazendo deploy do APP"'
    }
  }
}
