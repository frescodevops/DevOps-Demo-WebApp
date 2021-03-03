pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Init'
      }
    }

    stage('Static Code Analysis') {
      steps {
        echo 'Sonar Qube'
      }
    }

    stage('Build Web App') {
      steps {
        echo 'Build App'
      }
    }

    stage('Build Artifact') {
      steps {
        echo 'Build WAR file'
      }
    }

    stage('Upload to Artifactory') {
      steps {
        echo 'Upload to JFrog'
      }
    }

    stage('Deploy to QA') {
      steps {
        echo 'deploy to test'
      }
    }

    stage('Slack Notification') {
      steps {
        echo 'Notify On Slack'
      }
    }

    stage('UI-Test') {
      steps {
        echo 'Publish HTML Report'
      }
    }

    stage('Performance Test') {
      steps {
        echo 'Blazemeter Test'
      }
    }

    stage('Deploy to PROD') {
      steps {
        echo 'Launch in PROD'
      }
    }

    stage('Slack Notification-Prod') {
      steps {
        echo 'Notify on Slack'
      }
    }

    stage('Sanity-Test') {
      steps {
        echo 'Sanity Test'
      }
    }

  }
}