node {

      
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
