node {
  stage ('checking code') 
  {
   git 'https://github.com/Nihar5921/jenkins-git-maven-integrate.git'
  }
  stage ('compile package') 
  {
   sh 'mvn clean install' 
  }
}
