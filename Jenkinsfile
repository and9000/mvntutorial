node {
  def mvnHome = tool 'Maven 3.x'
  checkout scm
  sh "${mvnHome}/bin/mvn clean install"
}