pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Run Python Script') {
            steps {
                script {
                    sh 'python3 add.py'  // Replace '.py' with your actual Python file
                }
            }
        }
    }
}
