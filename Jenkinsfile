 pipeline{
    agent any
    stages{
        stage('Hello'){
            steps{
                echo 'Hello World from Pipeline'
            }
        }
        stage('Hi'){
            steps{
                echo "Hi World from Pipeline"
            }
        }
    }
  post{
     success{
      echo 'Pipeline Executed Succesfully'
     }
   failure{
     echo 'Pipeline failed, Check logs for details'
   }
  }
}
