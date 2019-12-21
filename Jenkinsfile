node{
     stage(scm checkout)
     {
     checkout changelog: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GIT', url: 'https://github.com/ppuhan/maven-web-project.git']]]
     }
     stage(test)
     {
     echo testing the source code
     }
     stage(package)
     {
     echo package the source code to binary artifact
     }
     
}
