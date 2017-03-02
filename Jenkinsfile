#!groovy

import static java.util.UUID.randomUUID

def generateGUID() {
  uuid = randomUUID() as String
  uuid.toUpperCase()
}

def PIPELINE_BRANCH_NAME = "Jira-752-Final"
def SOURCE_PATH = "Jira-752-Final"


node() {

  print "DEBUG: parameter PipelineUrl = ${PipelineUrl}"
  print "DEBUG: parameter TestProjectUrl = ${TestProjectUrl}"
  print "DEBUG: parameter NexusArtifact = ${NexusArtifact}"
  print "DEBUG: parameter DevServerName = ${DevServerName}"
  print "DEBUG: parameter DevPath = ${DevPath}"

//      env.UUID = generateGUID()
//      ws("D:/jenkins/development/workspace/${JOB_NAME}") {
//        env.WORKSPACE = pwd()
//
//        stage("Checkout") {
//          echo "${env.UUID}"
//
//          checkout([
//              $class           : 'GitSCM',
//              gitTool          : 'GIT_Windows_2.9',
//              branches         : [[name: "*/${BRANCH_NAME}"]],
//              extensions       : scm.extensions + [[$class: 'CleanBeforeCheckout']],
//              userRemoteConfigs: [[credentialsId: 'tfs online account', url: 'https://tfs-svm.visualstudio.com/DevOps/_git/PAC_Development_Project']]
//          ])
//          checkout([
//              $class           : 'GitSCM',
//              gitTool          : 'GIT_Windows_2.9',
//              extensions       : scm.extensions + [[$class: 'CleanBeforeCheckout']],
//              branches         : [[name: "*/${PIPELINE_BRANCH_NAME}"]],
//              extensions       : [[$class: 'RelativeTargetDirectory', relativeTargetDir: 'scripts']],
//              userRemoteConfigs: [[credentialsId: 'tfs online account', url: 'https://tfs-svm.visualstudio.com/DevOps/_git/PipelineScripts']]
//          ])
//
//          load "${env.WORKSPACE}/scripts/jsonvariables.txt"
//          load "${env.WORKSPACE}/scripts/environmentvariable.txt"
////                    load "${env.WORKSPACE}/scripts/EnvAction.txt"
//        }
//        load "${env.WORKSPACE}/scripts/PipelineStages.txt"
//
//      }
}