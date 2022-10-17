pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo 'Build'
            }

        }
        stage ('Test') {
            steps
             {
                echo 'Test'
            }

        }
        stage ('Sonarqube Gate') 
        {
            steps 
            {
                echo 'Sonarqube Gate'
            }

        }
        stage ('Push to Artifactory') 
        {
            steps
            {
                echo 'Push to Artifactory'
            }

        }
        stage ('Deploy to QA')
        {
            steps 
            {
                echo 'Deploy to QA'
            }
        }

        stage ('Deploy to Prod')
        {
            steps
            {
                echo 'Deploy to Prod'
            }
        }
    }

}
