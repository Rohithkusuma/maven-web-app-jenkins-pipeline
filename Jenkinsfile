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
    }
}  