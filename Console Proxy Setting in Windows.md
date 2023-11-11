# Console Proxy Setting in Windows

## In PowerShell:
```bash
$env:http_proxy="ip-address:8080"  
$env:https_proxy="ip-address:8080"
curl http://www.google.com
```
## In CMD:
```bash
set HTTP_PROXY=ip-address:8080  
curl -vv http://www.google.com
```
