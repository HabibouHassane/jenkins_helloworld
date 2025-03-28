node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/HabibouHassane/jenkins_helloworld'
 }
  stage('Build') {
    sh 'javac Main.java'
 }
  stage('Run') {
    sh 'java Main'
 }
}