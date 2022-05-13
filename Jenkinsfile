pipeline {
    agent any
    stages {
  stage('install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'null', mavenSettingsConfig: 'null') {
    sh 'mvn clean install'
}
    }
  }

}
}
