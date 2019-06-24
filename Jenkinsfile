node {
 stage('Checkout') {
           echo 'Checking Out..'

               checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'c57db2f9-fb84-4a71-bb03-4e132372cae3', url: 'http://192.168.1.250/Bonobo.Git.Server/DucenPlanIT.git']]])
       }

      
       stage('Build')
    {
     echo 'Build Started..'
        echo "[JenkinsDotNet] - Started"
                        powershell "dotnet msbuild .\\Targets.xml /t:'BuildServices'"
                        echo "[JenkinsDotNet] - Done"


    }


       stage('Test') {

               echo 'Testing..'

       }
       stage('Deploy') {

               echo 'Deploying....'

       }

}
