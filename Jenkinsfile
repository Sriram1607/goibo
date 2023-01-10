node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Sriram1607/Maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
