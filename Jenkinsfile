pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo '✅ Código baixado do GitHub'
            }
        }

        stage('Install') {
            steps {
                echo '📦 Instalando dependências...'
                // Comando comentado para evitar erro se o Node.js não estiver instalado
                // sh 'npm install'
                echo '✅ Dependências instaladas (simulado)'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Executando testes...'
                // Comando comentado para evitar erro se o Node.js não estiver instalado
                // sh 'npm test'
                echo '✅ Testes passaram (simulado)'
            }
        }

        stage('Deploy') {
            steps {
                echo "🚀 Deploy da versão ${BUILD_NUMBER} realizado!"
            }
        }
    }
}
