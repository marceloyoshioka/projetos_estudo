pipeline {
    agent any

    stages {
        stage('Ler Arquivo do GitHub') {
            steps {
                echo 'Listando arquivos do repositório...'
                sh 'ls -la'
                
                echo 'Conteúdo do mensagem.txt:'
                sh 'cat mensagem.txt'
            }
        }
    }
}
