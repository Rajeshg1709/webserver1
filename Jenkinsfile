pipeline {
	agent any 
	stages {
		stage('git checkout') {
		git 'https://github.com/Rajeshg1709/webserver1'
		}
		stage('install web') {
		steps {
		sh 'sudo chmod 777 install.sh'
		sh './install.sh'
		sh 'sudo cp ./index.html /var/www/html/index.html'
		}}}}
