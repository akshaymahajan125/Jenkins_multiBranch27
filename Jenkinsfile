node('built-in') 
{
    stage('Continuous Download_loan') 
   
	{
    git 'https://github.com/akshaymahajan125/maven.git'
	}
    stage('Continuous Build_loan') 
	{
    sh label: '', script: 'mvn package'
	}
    
	}
}
