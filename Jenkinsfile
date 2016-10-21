node {
  def mvnHome = tool 'Maven 3.x'
  sh "cd ${WORKSPACE}"
  sh "${mvnHome}/bin/mvn clean install"
}