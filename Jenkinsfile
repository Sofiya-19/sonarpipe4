pipeline {
    agent any
    stages {
        stage('Breakfast') {
            steps {
                echo "Had breakfast!"
            }
        }
        stage('Workout') {
            steps {
                echo "Completed workout!"
            }
        }
        stage('Study') {
            steps {
                echo "Studied effectively!"
            }
        }
        stage('FamilyTime') {
            steps {
                echo "Spent quality time with family!"
            }
        }
        stage('Play') {
            steps {
                echo "Had fun playing!"
            }
        }
    }
    post {
        success {
            echo "My day went well!"
        }
        failure {
            echo "Something went wrong today."
        }
    }
}
