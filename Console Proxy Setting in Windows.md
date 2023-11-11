# Console Proxy Setting in Windows

## In PowerShell:
```bash
$env:http_proxy="http://proxyau.huawei.com:8080"  
$env:https_proxy="http://proxyau.huawei.com:8080"  
curl http://www.google.com
```
## In CMD:
```bash
set HTTP_PROXY=http://proxyau.huawei.com:8080  
curl -vv http://www.google.com
```
