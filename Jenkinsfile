pipeline {
    agent any
    
    stages {
        stage('Checkout') { 
            steps {
                git url: 'https://github.com/buelvas/proyecto-jenkins.git', branch: 'main'
            }
        }
        
        stage('Build') { 
            steps {
                echo 'Compilando el código del proyecto...'
                sh 'echo "build ejecutado con exito"'
            }
        }
        
        stage('Test') { 
            steps {
                echo 'Ejecutando las pruebas automatizadas...'
                sh 'echo "Pruebas completadas con exito"'
            }
        }
        
        stage('Deploy') { 
            steps {
                echo 'Haciendo el despliegue...'
                sh 'echo "Despliegue realizado con exito"'
            }
        }
    }
}