pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh'''
        ls
        echo "Esto fue tomado de la branch 2"
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
