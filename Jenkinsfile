pipeline {
    agent any

    stages {
        stage('Clonar Repo') {
            steps {

                echo 'Clonacion de repo'
                git branch: 'main', url: 'https://github.com/IngCristhian/cristian-web.git'
                
            }
        }
    }
}
