pipeline
{
    agent any
    stages
    {
        stage('Clean Branch')
        {
            steps
            {
                 echo 'Clean Branch' 
            }
        }
        
}
        post {
      
        always 
        {
            emailext body: 'Your Job successfully Build', subject: 'Your Job successfully Build', to: 'tech.murali123@gmail.com'
        }

}
}    
