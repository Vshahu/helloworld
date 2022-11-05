if (env.BRANCH_NAME == "master") {
    properties([
        pipelineTriggers([
            pollSCM("H/5 * * * *")
        ])
    ])
}

pipeline {
    agent none

    stages {
        stage("greet the general") {
            steps {
                echo "hello there"
            }
        }
    }
}
@Vshahu
