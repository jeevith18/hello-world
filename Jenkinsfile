pipeline {
  agent any

  stages {
    stage("Hello") {
      steps {
        echo "Hello"
      }
    }
    stage("Branch Test") {
      when {
        // skip this stage unless branch is NOT master
       branch "main" 
      }
      steps {
        echo "World"
        echo "Heal it"
      }
    }
  }
}
