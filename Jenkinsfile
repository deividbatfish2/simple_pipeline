pipeline {
    agent any

    stages {
        stage('Baixar o projeto do repositório') {
            steps {
		echo 'Baixando o projeto do repositório remoto'
                git https://github.com/deividbatfish2/pipeline_teste.git
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
