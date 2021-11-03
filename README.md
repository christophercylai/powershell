# Powershell

## Uninstall Applications
```
$app = Get-WmiObject -Class Win32_Product -Filter "Name = 'NAME OF THE APPLICATION'"
$app.Uninstall()
```
