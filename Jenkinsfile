pipeline {
	agent { docker { image 'eclipse:ubuntu/latest' } }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                    pwd
                '''
            }
        }
                
        stage ('Build') {
            steps {
                sh 'mvn install -DskipTest -B -q' 
            }
        }
    }
}