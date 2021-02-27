Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco install winrar<br>
choco install googlechrome

choco install opera

choco install filezilla

choco install visualstudio2019community
choco install sql-server-2019
choco install sql-server-management-studio
choco install notepadplusplus
choco install vscode
choco install nodejs
choco install github-desktop
choco install postman


choco install docker-desktop
choco install composer


choco install vmwareworkstation
