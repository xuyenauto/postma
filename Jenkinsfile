pipeline{
    agent{
        label "xutra"
    }
    stages{
        stage('Run scripts'){
            steps{
                 echo "Hello World!"
                 sh "newman run --disable-unicode topdm_api_investigate.postman_test_run.json -e QA_ENV_Practice.postman_environment.json exit 1"
            }
        }
    }
}