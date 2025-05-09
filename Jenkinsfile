pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Clone the repository
                git 'https://github.com/Ikkhan9110/73Exam.git'
            }
        }

        stage('Simple Step') {
            steps {
                echo 'This is a basic Jenkins pipeline that works!'
            }
        }
    }
}
