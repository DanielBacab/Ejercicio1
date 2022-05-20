pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Do something"
        }
    }
      stage('Test'){
        steps{
            echo "Do something else"
            sh '''
            ls
            pwd
            uname
           
        }
      }
      stage('Deploy'){
        steps{
            echo "Here goes nothing"
            echo $Prueba
        }
      }
    }
  }   
