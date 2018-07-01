pipeline {
    agent any
    stages {

        stage('testing pipeline'){
          steps{
		    echo 'test1'
                sh 'rm -rf from-jenkins'
                sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
                }
        }
        stage('second testing pipeline'){
          steps{
		    echo 'test2'
                sh 'rm -rf test2'
                sh 'mkdir test2'
                sh 'touch test2/test.txt'
                }
        }
                stage('third testing pipeline'){
          steps{
		    echo 'test3'
                sh 'rm -rf test3'
                sh 'mkdir test3'
                sh 'touch test3/test.txt'
                }
        }

}
}
