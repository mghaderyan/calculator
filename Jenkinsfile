pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage("Compile") {
            steps {
                echo 'Compile step'
            }
        }
        stage("Unit test") {
            steps {
                echo 'Unit test step'
            }
        }
    }
}
