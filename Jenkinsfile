pipeline {
    agent any

    stages {
        stage('Print Hello World - edited') {
            steps {
                sleep 11
                echo 'Hello World'
            }
        }

        stage('Edited stage - 2') {
                    steps {
                        sleep 7
                        echo 'Hello World 2'
                    }
                }

         stage('New stage - 3') {
                            steps {
                                sleep 3
                                echo 'Hello World 3'
                            }
                        }

        stage('New stage - 4') {
                                    steps {
                                        sleep 30
                                        echo 'Hello World 4'
                                    }
                                }

        stage('New stage - 5') {
                                    steps {
                                        sleep 20
                                        echo 'Hello World 5'
                                        error 'Force failure at the end of stage 5'
                                    }
                                }
    }
}
