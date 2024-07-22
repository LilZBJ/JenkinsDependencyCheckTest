pipeline {
  agent any
  stages {
    stage('Checkout SCM') {
      steps {
        dependencyCheck 'OWASP Dependency-Check Vulnerabilities'
        dependencyCheck 'OWASP Dependency-Check Vulnerabilities'
      }
    }

    stage('OWASP dependency check') {
      steps {
        dependencyCheckPublisher()
      }
    }

  }
}