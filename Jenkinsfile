node 
{
    stage ('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'bitbucket', url: 'http://192.168.0.108:7990/scm/proj2/rep02.git']]])
    }
}
