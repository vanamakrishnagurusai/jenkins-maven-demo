pipeline {
 agent any
 tools {
 jdk 'JDK-21'
 maven 'Maven-3'
 }
 stages {
 stage('Maven Build') {
 steps {
 sh 'mvn clean package'
 }
 }
 }
}

