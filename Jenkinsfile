pipeline
{
    agent none
    stages
    {
        stage('first test')
        {
            agent {label 'slave1'}
            steps
            {
                sh 'echo Hello world'
            }
        }
        stage('second test')
        {
            agent any
            steps
            {
                sh 'echo this is second stage'
            }
        }
        stage('third test')
        {
            agent any
            steps
            {
                sh 'echo this is third stage'
            }
        }
        
    }
}
