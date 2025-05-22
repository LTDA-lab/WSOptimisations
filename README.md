Before running the script, you must enable script execution on your Windows Server.
1- Run PowerShell as administrator and execute the following command: Set-ExecutionPolicy RemoteSigned -Force
2- Then right-click on the downloaded "WSOptimisations.ps1" and click Properties. Copy the path to the file location.
3- In PowerShell (Administrator), type "cd <path to the copied "WSOptimisations.ps1"> and press Enter.
4- Type "./WSOptimisations.ps1" and press Enter.
Examples:
Set-ExecutionPolicy RemoteSigned -Force
cd C:\Users\Administrator\Desktop
./WS2016Optimisations.ps1
