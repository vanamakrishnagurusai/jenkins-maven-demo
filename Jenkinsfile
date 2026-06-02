pipeline {
 agent any
 tools {
 jdk 'JDK-17'
 maven 'Maven-3'
 }
 stages {
 stage('Clone Code') {
steps {
 git branch: 'main', url: 'https://github.com/YOUR-USERNAME/jenkins-maven-demo.git'
 }
 }
 stage('Maven Build') {
 steps {
 sh 'mvn clean package'
 }
 }
 }
}

