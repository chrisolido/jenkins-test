pipeline {
    agent any
    stages {

        stage('testing pipeline'){
          steps{
		    echo 'test1'
                sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
                }
        stage('testing pipeline'){
          steps{
		    echo 'test1'
                sh 'mkdir test'
                sh 'touch test/test.txt'
                }
        }

}
}
