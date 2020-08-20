pipeline{
        agent any
        stages {
            stage('Lint HTML'){
                steps {
                    sh 'echo "Hello World"'
                }
            }
            stage('Upload to AWS') {
                steps {
                    retry(3){
                        withAWS(region:'us-west-2', credentials:'aws-static'){
                      
                    }                             
                }
            }
        }
    }
}