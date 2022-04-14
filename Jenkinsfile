properties([parameters([string(defaultValue: 'arik', description: 'what is your name?', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/ArikAtiya/RunViaJenkins.git"
    }
    stage("bla"){
        sh "ls -l"
    }
}