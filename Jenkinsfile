node {
  def mvnHome = tool 'Maven 3.x'
  def pwd = sh "pwd"
  sh "cd ${pwd}"
  sh "${mvnHome}/bin/mvn clean install"
}