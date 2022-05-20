pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh'''
        ls
        echo "Esto fue tomado de la brach 3"
        uname
        echo $Prueba
        hostname
        touch 1
        pwd

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
