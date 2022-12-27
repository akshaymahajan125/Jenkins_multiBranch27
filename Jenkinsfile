node('built-in') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/akshaymahajan125/maven.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}

	}
}
