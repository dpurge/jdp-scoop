# JDP Scoop

This is my personal scoop bucket.

## Installation

```powershell
[environment]::setEnvironmentVariable('SCOOP', 'D:\dat\scoop', 'Machine')
Invoke-WebRequest -UseBasicParsing get.scoop.sh | Invoke-Expression
scoop bucket add extras
scoop bucket add jdp https://github.com/dpurge/jdp-scoop.git
```

## Applications

```powershell
scoop install youtube-dl
scoop install bazel
scoop install joplin
scoop install pdftk
```

## Cleanup

```powershell
scoop cache rm bazel
scoop cache rm youtube-dl
```
