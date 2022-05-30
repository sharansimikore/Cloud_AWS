pipeline{

agent any
  stages{
  
    stage('Cloning'){
      echo "Clode is cloning from Github"
      git branch: 'main', url: 'https://github.com/sharansimikore/java-hello-world-with-maven.git'
      echo "Code is cloned from GitHub Repository"
      
    }
    
    stage('Build'){
    
      echo "Building code using maven tool"
      sh './mvnw package'
      echo "Build is done using maven tool"
    }
    
    stage('Test'){
    
    echo "Testing the code"
    echo "Checking jar file in target"
    
    }
    
    
    
  }
  
  
}
