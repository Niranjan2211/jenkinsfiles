#!/usr/bin/env groovy
pipeline {
    agent any
    environment {
        file_listener="dgi.filelistener"
        file_processor="dgi.fileprocessor"
        metadata_contentvalidator="dgi.metadatacontentvalidator"
        json_formatter="dgi.jsonformatter"
		}

    stages {
        stage('Preparation') {
            steps {
                echo '14'
            }
        }
        stage('Maven Build') {
            steps {
                echo 'Maven Build..'
            }
        }
        stage('Sonarqube Scanner') {
            steps {
                echo 'Sonarqube Scanner....'
            }
        }
		stage('Fortify Scan') {
            steps {
                echo 'Fortify Scan....'
            }
        }
		stage('Copy artifacts') {
            steps {
                echo 'Copy artifacts....'
            }
        }
		stage('Deploy in Dev Environemnt') {
            steps {
                echo 'Deploying in Dev Environemnt....'
            }
        }
		stage('Deploy in UAT Environemnt') {
            steps {
                echo 'Deploying in UAT Environemnt....'
            }
        }
		stage('Deploy in Prod Environemnt') {
            steps {
                echo 'Build 12 ....'
            }
        }
		
		
	
	
	} // stage 14
} //pipeline
