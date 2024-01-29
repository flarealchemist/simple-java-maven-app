pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/opt/apache=mavern-3.9.6/bin/mvn -B -DskipTests clean package'
      }
    }
  }
}
