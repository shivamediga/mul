node('master') 
{
    stage('Continuous Download_loanss') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loanss') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
