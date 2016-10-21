node {
  def mvnHome = tool 'Maven 3.x'
  sh "cd ${manager.build.getEnvVars()['WORKSPACE']}"
  sh "${mvnHome}/bin/mvn clean install"
}