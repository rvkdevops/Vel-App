pipeline {
    agent{
        label {
            label "slave-1"
        }
    }

    stages {
        stage("one") {
            steps {
                sleep 10
            }
        }

        stage("two") {
            steps {
                sleep 10
            }
        }

        stage("three") {
            steps {
                sleep 10
            }
        }
    }
}
