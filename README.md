# Automated Pull or Push Script

This is a Git Script for macOS, Windows, or Linux to automatically push or pull commits.

# Usage

## [How to Run Terminal Files on macOS / Linux](https://support.apple.com/guide/terminal/make-a-file-executable-apdd100908f-06b3-4e63-8a87-32e71241bab4/mac)

Shell scripts must be executable files in order to run. You can use the chmod command to indicate that the text file is executable (that is, its contents can be run as a shell script).
1. In the Terminal app on your Mac, use the cd command to move into the directory that contains the file you want to make executable. For example:
```
% cd YourScriptDirectory
```
2. Enter the chmod command. For example:
```
% chmod 755 YourScriptName.sh
```
3. After making the shell script file executable, you can run it by entering its pathname. For example:

```
% ~/Documents/Dev/YourScriptName.sh
```
or
```
% cd ~/Documents/Dev/ 
% ./YourScriptName.sh
```

## [How to Run Terminal Files on Windows](https://www.windowscentral.com/how-create-and-run-batch-file-windows-10)

1. Download the [push](https://github.com/Aarav-Batra/auto-push-pull-script/blob/main/Windows_push.bat) or [pull](https://github.com/Aarav-Batra/auto-push-pull-script/blob/main/Windows_pull.bat) file.
2. Double click the file when it has finished downloading, and it will run automatically.
