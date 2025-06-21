pipeline {
  agent any
  // stages {
  //   stage('Checkout') {
  //     steps {
  //       checkout scm
  //     }
  //   }
    stage('Hello') {
      steps {
        echo "Hello from Organization Jenkinsfile - I am from ${env.BRANCH_NAME}"
      }
    }

    stage('Hello Again') {
      steps {
        echo "The build Id was: ${BUILD_ID}"
      }
    }

    stage('Bye Now') {
      steps {
        echo "Jenkins Agent for this build was: ${JENKINS_AGENT_NAME}"
        echo "Git commit hash: ${GIT_COMMIT}"
      }
    }
  }
}
