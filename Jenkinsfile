pipeline {
			agent any 
			stages {
				stage('BUILD') {
					steps {
						sh '''
							#!/bin/bash 
							echo "This is a fist build stage in Jenkinsfile"
							'''
					}
				}
				stage('Test1') {
					steps {
						sh 'echo "1st test stage in Jenkinsfile"'
					}	
				}
				stage('Test2') {
					steps {
						sh 'echo "2nd test stage in Jenkinsfile"'
					}	
				}
				stage('DEPLOY') {
					steps {
						sh 'echo "Final DEPLOY stage in Jenkinsfile"'
					}
				}
			}
		}
