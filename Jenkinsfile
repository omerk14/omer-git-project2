properties([pipelineTriggers([pollSCM('* * * * * ')])])
node {
    stage("clone") {
        git "https://github.com/omerk14/omer-git-project2.git"
    }
    stage("show files"){
        bat "dir"
    }
}
