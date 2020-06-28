# 同站和同源

## Origin（源）

`origin` 是由协议、主机名、端口组成。例如 `https://www.example.com:443/foo` 的 `origin` 就是 `https://www.example.com:443`。

### 同源

协议、主机名、端口都相同被视为同源。

## Site（站）

`site` 是由 `eTLD`（有效顶级域名）和他前面部分域的组合。例如 `https://www.example.com:443/foo` 的 `site` 就是 `example.com`。

### 同站

`eLTD` + 前面部分域名相同被视为同站。
