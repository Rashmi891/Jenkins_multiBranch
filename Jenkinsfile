node('build_in') 
{
    stage('Continuous Download_child') 
	{
    git 'https://github.com/KranthiGajjelli/Maven.git'
	}
    stage('Continuous Build_child') 
	{
    sh label: '', script: 'mvn package'
		}
}
