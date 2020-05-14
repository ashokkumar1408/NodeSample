pipeline{
    agent{
        dockerfile true
    }
    stages{
        stage('Build'){
            steps{
                echo 'Hello World'
                sh 'node --version',
                sh 'svn --verison'
            }
        }
       // stage('Docker Build')
    }
}