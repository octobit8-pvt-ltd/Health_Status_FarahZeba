pipeline{
    agent any 
    stages{
        stage("Build"){
            steps{
                script {
                    bat 'python health_status_app.py'
                }
            }
        }
    }
}