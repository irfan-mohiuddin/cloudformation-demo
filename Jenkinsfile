pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId: 'aws-key', usernameVariable: 'AKIA42SW3YUU42PQSHQG
', passwordVariable: '9XvgpAFkzG44CN7p5kxqTAxzxfK9UfPXWvZVoWaF
']])
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3cft.yml --region 'us-east-1'"
              }
             }
            }
            }
