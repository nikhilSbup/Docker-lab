CODE_CHANGES = getGitChanges()
pipeline {
  agent any
  stages{
    stage('build'){
      when{
        expression {
          BRANCH_NAME == 'master' && CODE_CHANGES = true
        }
      }
      step{
        echo 'building the application...'
      }
    }
    stages('test'){
       when{
        expression {
          BRANCH_NAME == 'development
        }
      }
      steps{
        echo 'testing the application..."
      }
      
    stages('deploy'){
      steps{
        echo 'testing the application..."
      }
    
