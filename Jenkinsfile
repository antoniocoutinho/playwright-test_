#!/usr/bin/groovy
import groovy.json.JsonOutput

pipeline {
    agent { 
                label 'pwalias'
            }

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
