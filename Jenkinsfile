pipeline {
  agent any
  stages {
    stage('Rake test') {
      steps {
        sh '''#!/bin/bash

bundle update
bundle exec rake test'''
      }
    }
    stage('') {
      steps {
        echo 'Tests done!'
      }
    }
  }
}