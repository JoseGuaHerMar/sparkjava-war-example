pipeline {
    agent { label 'agente1' }
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola"
                echo $prueba
                pwd
                ls -lrt
                echo $password
                pwd
                uname
                docker ps
                hostname
                touch 1
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
               pwd
               echo "hola"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
              echo "Adios"
              ls
              
                '''
            }
        }
    }
}
