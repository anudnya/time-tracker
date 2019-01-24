
pipeline {
    agent any
    tools { 
        maven '/opt/maven'
    }
    stages{
        stage ('Build'){
            steps{
	        echo 'Maven Build'
                sh 'mvn install'
            }
	}
    }
}
