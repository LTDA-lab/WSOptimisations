Before running the script, you must enable script execution on your Windows Server.

1- Run PowerShell as administrator and execute the following command: Set-ExecutionPolicy RemoteSigned -Force

2- Then right-click on the downloaded "WSOptimisations.ps1" and click Properties. Copy the path to the file location.

3- In PowerShell (Administrator), type "cd <path to the copied "WSOptimisations.ps1"> and press Enter.

4- Type "./WSOptimisations.ps1" and press Enter.

Examples:

Set-ExecutionPolicy RemoteSigned -Force

cd C:\Users\Administrator\Desktop

./WSOptimisations.ps1

source: https://jgspiers.com/windows-server-2016-optimisation-script/

Tested on Windows Server 2016, 2019, and 2022


![2025-05-22 05_51_42-Greenshot](https://github.com/user-attachments/assets/4eb91880-9888-4b8f-a1d2-d20c344a425d)
