pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh'''
        ls
        echo "hola"
        uname
        echo $Prueba
        hostname
        touch 1
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
