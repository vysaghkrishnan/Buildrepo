pipeline 
{
    agent any

    stages 
    {
        stage('Docker Build') 
        {   
            steps 
            {
                sh 'pwd'
                sh 'ls -al'
		sh 'docker version'
                sh 'echo "Creating Docker Image..."'
		sh 'docker build -t vysaghkrishnan/mypython:1.0 .'
            }
        }
    }
}
