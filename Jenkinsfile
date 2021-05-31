node('master') 
{
    stage('ContinuousDownload')
    {
        git 'https://github.com/JavaExp/maven.git'             
    }
    stage('ContinuousBuild')
    {
        sh 'mvn package'
    }
    
}
