node 
{
    stage ('checkout')
    {
        checkout([$class: '', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/ambatigit/website.git']]])
    }
}
