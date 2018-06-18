pipeline {
	agent { docker { image 'maven:3.5.3-jdk-8-slim' } }
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