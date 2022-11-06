pipeline {
    agent none
    stage('Git Push'){
    steps{
        script{
           
            sh '''
                git add .
                git commit -m "push to git"
                git push https://github.com/Vshahu/helloworld.git feature
            '''
        }
    }
}
}
@Vshahu
