pipeline {
    agent any
    stages {
  stage('install') {
    steps {
      withMaven(maven: 'maven3') {
    sh 'mvn clean install'
}
    }
  }

}
}
