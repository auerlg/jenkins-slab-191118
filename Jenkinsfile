pipeline {
    agent any
    stages {
        stage('Stage1 sanitiy check') {
            steps {
                sh 'ping -c 5 google.com'

            }
        }
        stage('Stage2 integrity check') {
            steps {
                sh '''
                        for i in {1..5}
                        do
                        echo "Welcome $i times"
                        done
                    ''' 

            }
        }
        stage('Stage3 apache check') {
            steps {
<<<<<<< HEAD
                sh ' curl 192.168.56.211:80' 
=======
                sh '''
                    curl 192.168.56.211:80
                    ''' 
>>>>>>> cf01e49c0863e6d06f35c6fd09d7d354a41f4035

    }
}