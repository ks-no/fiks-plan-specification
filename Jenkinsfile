pipeline {
    agent any
    stages {
        stage('Trigger dotnet build jobs') {
            when {
                anyOf {
                    branch 'main'
                    branch 'bygg_dotnet_models'
                }
            }
            steps {
                build job: '/KS/fiks-plan-models-dotnet/jenkins_pipeline', parameters: [[$class: 'StringParameterValue', name: 'triggerbranch', value: env.BRANCH_NAME]]
            }
        }
    }
}