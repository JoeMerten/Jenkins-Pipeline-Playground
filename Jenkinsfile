#!/usr/bin/env groovy

//apply from: 'https://raw.githubusercontent.com/org-name/repo-name/master/subfolder/Jenkinsfile?token=${env.GITHUB_TOKEN}'
apply from: 'https://raw.githubusercontent.com/JoeMerten/Jenkins-Pipeline-Playground/master/Jenkinslib.groovy'

ansiColor('xterm') {

node() {
    stage("Init") {
    	echo "Initializing"
    }

    stage("Work") {
    	echo "Do some work"
    }

    stage("Quit") {
    	echo "Cleanup"
    }
} // node

} // ansiColor
