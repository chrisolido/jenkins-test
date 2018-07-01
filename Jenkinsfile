pipeline {
    agent any
    stages {

        stage('testing pipeline'){
          steps{
		    echo 'test1'
                sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
                }
        }
        stage('second testing pipeline'){
          steps{
		    echo 'test2'
                sh 'mkdir test2'
                sh 'touch test2/test.txt'
                }
        }

}
}
