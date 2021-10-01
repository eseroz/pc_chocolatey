
###################### CHOCOLATEY INSTALLATION LIST ######################
<br><br>
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco install winrar<br>
choco install googlechrome<br>
choco install opera<br>
choco install filezilla<br>
choco install visualstudio2019community<br>
choco install sql-server-2019<br>
choco install sql-server-management-studio<br>
choco install notepadplusplus<br>
choco install vscode<br>
choco install nodejs<br>
choco install github-desktop<br>
choco install postman<br>
choco install docker-desktop<br>
choco install composer<br>
choco install vmwareworkstation<br>
choco install jq


###################### HOW TO USAGE DOCKER ######################<br><br>
Sql Server installation<br>
Docker run --restart unless-stopped  -e "ACCEPT_EULA=Y" -v D:\DBYEDEK:/gk_data -e "SA_PASSWORD=Ankara!06" -p 1501:1433 --name sql1 -d mcr.microsoft.com/mssql/server:2019-latest
