# Console Proxy Setting in Windows

## In CMD:
```bash
set proxy_ip=
set HTTP_PROXY=%proxy_ip%:8080
curl -vv http://www.google.com
```

## In PowerShell:
```bash
$env:http_proxy="proxy_ip:8080"
$env:https_proxy="proxy_ip:8080"
curl http://www.google.com
```

## Test pip outer source index e.g. Tsinghua
```
pip uninstall pandas -y
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pandas
```
