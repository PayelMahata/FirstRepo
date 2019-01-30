node()
{
    stage("Checkout")
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Git-Trainingport', url: 'https://github.com/trainingport/trainingrepo']]])
    }
    stage("Build")
    {
        echo "Building"
    }
}
