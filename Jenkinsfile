properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("dir test branch")
    {
        bat "dir"
    }
    stage{
        bat "python 1.py"
    }
}
