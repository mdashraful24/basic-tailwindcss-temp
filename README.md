## Most Important ##

## Not working npm in vscode terminal

# Enable
1. Temporarily Bypass Execution Policy (Recommended)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Disable
1. Set Execution Policy to Restricted (Disable Script Execution)
Set-ExecutionPolicy -ExecutionPolicy Restricted -Scope CurrentUser

2. Verify the Execution Policy
Get-ExecutionPolicy -Scope CurrentUser

3. Completely Reset Execution Policy (Optional)
Set-ExecutionPolicy -ExecutionPolicy Undefined -Scope CurrentUser
