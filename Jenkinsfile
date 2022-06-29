pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
	    bat "git clone https://github.com/pintu121/app1.git"
               // echo 'Code Build By Pintu Patra.'
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
