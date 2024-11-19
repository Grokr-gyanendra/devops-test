pipeline{
    agent any

    stages{
        stage('Work'){
            steps{
                echo "Working...."
            }
        }
        stage('Run'){
            steps{
                script{
                    sh "python app.py"
                }
            }
        }
    }
}
