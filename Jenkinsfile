node{
    stage('Poll'){
        checkout scm
    }
    stage('Build & Unit test'){
        sh 'mvn clean '
    }
}