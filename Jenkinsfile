node {
  def mvnHome = tool 'Maven 3.x'
  sh "cd ${env.WORKSPACE}"
  sh "${mvnHome}/bin/mvn clean install"
}