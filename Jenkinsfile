pipeline {
    agent any
    environment {
        CELEBRITY = 'Tejaswi' //onment directive used in the top-level pipeline block will apply to all steps within the pipeline
            }
    stages {
        stage('Example') {
            environment {
                API_KEY = 'ISCP123' //An environment directive defined within a stage will only apply the given environemtn variables to steps within the stage
            }
            steps {
                sh 'printenv'
            }
        }
    }
    }


