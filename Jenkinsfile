pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
            bat 'mvn clean package deploy -DskipMunitTests -DmuleDeploy -DmuleVersion=4.4.0 -Dusername="Suprabath0911" -Dpassword="Kristam@0910" -DapplicationName=cicddemotest -Denvironment=Sandbox -DbusinessGroup="Apisero Demo" -DworkerType=MICRO  -Danypoint.platform.client_id=1e11150f98e44b8fb092624bcba1cee1 -Danypoint.platform.client_secret=84b63d46429D438FBC248f51874f5079
    }
	}
	
}