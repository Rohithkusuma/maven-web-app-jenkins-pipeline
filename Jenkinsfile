pipeline{
  agent any
  environment {
    PATH="$PATH:/opt/apache-maven-3.6.3/bin"  
  }
  stages{
    stage('GetCode'){
        steps{
                git branch: 'master',
                url:  'https://github.com/Rohithkusuma/Maven-webapp-int.git'
        }
      }  
   stage('Build'){
        steps{
          sh 'mvn clean package'  
        }
      }
<<<<<<< HEAD
  }
}  
=======
   }
}  
>>>>>>> 9484bc001fd74e506c7c495f6ec39baeb59cb301
