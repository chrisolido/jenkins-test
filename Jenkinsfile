pipeline {
    agent any
    stages 1 {

        stage('Step 1 pipeline'){
          steps{
		    echo 'test1'
                sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
                }
        }
        }
        stages 2 {

        stage('Step 2 pipeline'){
          steps{
		    echo 'test1'
                sh 'ls'
                sh 'ls -la'
                }
        }
        }
}

