pipeline {
    agent any
    stages {
        stage('Trigger dotnet build jobs') {
            steps {
                build job: '/KS/fiks-plan-models-dotnet/main', parameters: [[$class: 'StringParameterValue', name: 'triggerbranch', value: env.BRANCH_NAME]]
            }
        }
    }
}