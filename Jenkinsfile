properties([gitLabConnection('ADOP Gitlab')])

node('docker') {

    def branch = env.BRANCH_NAME

    mavenMultiBuildPipeline {
        pipelineBranch = branch
    }

}
