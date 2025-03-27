pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/salman123-sudo/pythonscript.git'
            }
        }

        stage('Run Python Script') {
            steps {
                script {
                    sh 'python3 add.py'  // Replace 'add.py' with your actual Python file
                }
            }
        }
    }
}
