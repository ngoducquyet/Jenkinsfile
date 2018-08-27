def workspace;
node
{
    stage("Checkout")
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/ngoducquyet/Jenkinsfile.git']]])
        workspace = pwd() 
    }
    stage("Static Code Analysis")
    {
        echo "Static Code Analysis"
    }
    stage("Build")
    {
        echo "Build the code"
    }
    stage("Unit Test")
    {
        echo "Build the code"
    }
    stage("Delivery")
    {
        echo "Delivery the code 27 Aug"
    }
}
