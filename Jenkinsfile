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
    }
}