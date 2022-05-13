pipeline {
    agent any
    stages {
  stage('install') {
    steps {
      withMaven(maven:'maven-3') {
    sh 'mvn clean install'
}
    }
  }

}
}
