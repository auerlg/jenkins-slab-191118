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
                sh '''
                    curl 192.168.56.211:80
                    ''' 

    }
}