pipeline {
    agent any
    environment {
        LEGEND =  'srinath' ////An environment directive used in the top-level pipeline block will apply to all steps within the pipeline
            }
    }
    stages {
        stage('Example') {
            environement {
                API_KEY = 'ISCP123' //An environment directive defined within a stage will only apply the given environemtn variables to steps within the stage
            }
            steps {
                sh 'printenv'
            }
        }
    }
    }
}
