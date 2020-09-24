# Install Windows Toolset

```shell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iwr https://raw.githubusercontent.com/McCodeman/antrea-capv-demo/master/tools/windows/init-tools.ps1 -UseBasicParsing | iex
```