# Console Proxy Setting in Windows

## In PowerShell:
```bash
$env:http_proxy="ip-address:port"  
$env:https_proxy="ip-address:port"
curl http://www.google.com
```
## In CMD:
```bash
set HTTP_PROXY=ip-address:port  
curl -vv http://www.google.com
```
