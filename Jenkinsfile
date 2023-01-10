node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/Sriram1607/Maven.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
