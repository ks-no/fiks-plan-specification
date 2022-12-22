pipeline {
    agent any
    stages {
        stage('Trigger build jobs'){
          parallel {
            stage ('dotnet') {
              steps {
                build job: '/KS/fiks-plan-models-dotnet/hs/jenkins_pipeline', parameters: [[$class: 'StringParameterValue', name:'triggerbranch', value: env.BRANCH_NAME]]
              }
            }            
          }
        }
    }
}