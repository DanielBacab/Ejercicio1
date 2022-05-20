pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh'''
        ls
        echo "Esto es el main"
        uname
        echo $Prueba
        hostname
        touch 1
        pwd
        echo "nuevo"
        '''
  
        }
    }
      stage('Test'){
        steps{
            echo "Do something else"
        }
      }
      stage('Deploy'){
        steps{
            echo "Here goes nothing"
            
        }
      }
    }
  }   
