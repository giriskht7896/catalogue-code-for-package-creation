pipeline{
    agent{node { label'agent-1'} }
    stages{
        stage('install dependencies'){
            steps{
                sh 'npm install'
            }
        }
        stage('unit test'){
            steps {
                echo "unit testing is done here"
            }
        }
        stage('sonar scan'){
             steps {
                sh 'sonar-scanner'
        }
        }
       
    }
}