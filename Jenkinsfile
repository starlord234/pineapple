pipeline{
   agent any
     tools {
      maven 'maven'
     }
        stages{
          stage('get latest code'){
            steps{
            echo 'get latest code'
            git 'https://github.com/starlord234/pineapple.git'
        }
      }
    }
  }

