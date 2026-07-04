# What is ShellCheck
ShellCheck is a static analysis tool that does exactly what PSScriptAnalyzer does, but for sh, bash, dash, and ksh scripts. 

# How to use ShellCheck
## 1. Install the Tool
Since it is a compiled tool, you install it via your system's package manager:

Windows (via Winget):
```
winget install koalaman.shellcheck
```
Linux (Ubuntu/Debian):
```
sudo apt install shellcheck
```
## 2. How to Use It
Once installed, you can point it at any .sh file to get a report of warnings, errors, and best-practice violations.

To scan a specific script, use this command:
```
shellcheck ./your_script.sh
```
If you use VS Code, there is also an official ShellCheck extension that will highlight your .sh files with squiggly lines in real-time as you type, just like a modern IDE.
