### Setup pipeline in Jenkins Steps

1. Download latest nuget from here: https://www.nuget.org/downloads
2. Put nuget.exe in C:\Program Files (x86)\Nuget\ folder and Envirnment variable in system path

3. Install following package via choco

    . choco install -y microsoft-build-tools --version=14.0.25420.1
    
    . choco install -y msdeploy3 
    
    . choco install -y visualstudio2017buildtools 
    
    . choco install -y visualstudio2017-workload-webbuildtools 
