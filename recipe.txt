# ChocoInstallBase.ps1 by atwork.at
# Get Chocolatey
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

# See packages at https://chocolatey.org/packages/
# Use according to your own needs...

# Essentials
choco install notepadplusplus -y

choco install googlechrome -y

choco install vlc -y

# Msft & Office
choco install Office365ProPlus -y

choco install skype -y

# Additional Tools
choco install winrar -y

# Dev
choco install git -y
choco install vscode -y
choco install postman -y
choco install fiddler -y

# Microsoft .NET Framework Developer Pack
choco install netfx-4.8-devpack
# Microsoft .NET Core
choco install dotnet-sdk
# More Dev
choco install sql-server-management-studio -y
choco install sql-server-2019 -y
