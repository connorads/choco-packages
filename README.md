# choco-packages
@connorads favourite Chocolatey packages 🍫

#### Install choco packages

If you already have Chocolatey installed

`choco install packages.config -y`

#### Install choco

Here's a quick way to install Chocolatey on Windows 10

1.  Open PowerShell (Admin)  
   <kbd>win</kbd> + <kbd>x</kbd> , then press <kbd>a</kbd>

2. From PowerShell, open Command Prompt (Admin)  
   `cmd`

3. Install Chocolatey  

   ~~~~
   @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
   ~~~~

4. *(Optional)* Refresh environment variables for current session  
   `refreshenv`

#### Upgrade all choco packages

`choco upgrade all -y`