---
type: literature
date: 2026-03-20
source: Analyze log file entries that SFC.exe generates - Windows Client
url: https://learn.microsoft.com/en-us/troubleshoot/windows-client/installing-updates-features-roles/analyze-sfc-program-log-file-entries
author: 
tags: [windows]
public: true
---

# Analyze log file entries that SFC.exe generates - Windows Client

## Summary
CBS Path: `%windir%\logs\cbs`

```powershell
findstr /c:"[SR]" %windir%\logs\cbs\cbs.log > sfcdetails.txt
```
## Key Ideas

## Quotes

## My Thoughts

