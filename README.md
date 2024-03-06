# PowerShell
PowerShell is a task automation and configuration management program from Microsoft, consisting of a command-line shell and the associated scripting language.

*PowerShell file format .ps1

* Get-Command
```
  >Get-Command *Service* // cmdlets that contain the word ‘service’
```
* Get-Help
```
> Get-Help Restart-Service
```
* Variable
```
>$a=30
```
* Array
```
>$nameArray = @("john", "Joe", "Mary")
>$nameArray[0]
```
* Hashtable
```
> $user=@{FirstName="John"; LastName="Smith"; MiddleInitial="J"; Age=40}
> $User.LastName
```
```shell
>PSVersionTable
>PSVersionTable.PSVersion

>New-Item -Name "Desk" -Type Directory
>New-Item -Name "test.py" -ItemType File
>echo 'print("HelloWorld")' > test.py

>Get-Process //list running processes
>Get-ChildItem //Shows files and directories (similar to dir)
>Set-Location //Changes the current directory (similar to cd)
```
Link: https://learn.microsoft.com/en-us/training/paths/get-started-windows-powershell/
