## Log Management

#### Backup-Files.ps1
Designed to backup flat files within a single folder location.  Collection of files will be taken and grouped by creation date.  Each date will be zipped and moved to destination location.


#### Backup-Folders.ps1
This script will backup log folders, folders should be named in the 'yyyyMMdd' format.  Each folder will be zipped and moved to destination.


#### Backup-OSLogs.ps1
Obtains collection of computer names from domain security group.  Each will be processed and the Application, Security, and System logs will be shipped to storage location.