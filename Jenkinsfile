node {
  stage ('checking code') 
  {
   git 'https://github.com/Nihar5921/jenkins-git-maven-integrate.git'
  }
  stage ('compile package') 
  {
   sh 'mvn package' 
  }
  stage ('war test')
  {
    sh 'sudo cp var/lib/jenkins/workspace/1st_maven/target/sparkjava-hello-world-1.0.war /opt/tomcat/apache-tomcat-9.0.45/webapps'
  }
}
