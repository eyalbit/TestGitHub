properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("dir test branch")
    {
        bat "dir"
    }
    stage{
        git "https://github.com/eyalbit/TestGitHub.git"
    }
    stage{
        bat "python 1.py"
    }
}
