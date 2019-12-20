node{
     stage(scm checkout)
     {
     checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], 
     submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GIT', url: 'https://github.com/ppuhan/maven-web-project.git']]])
     }
     stage(test)
     {
     testing the source code
     }
     stage(package)
     {
     package the source code to binary artifact
     }
     
