https://zenn.dev/yazan/articles/0663e6e4680042# ngrok_test_2502

# docker 起動
``` docker compose up -d ```

# ngrok 起動
``` ngrok http http://localhost:8080 ```

```
Session Status                online
Account                       krcklcp10nknk@gmail.com (Plan: Free)
Version                       3.19.1
Region                        Japan (jp)
Latency                       44ms
Web Interface                 http://127.0.0.1:4040
Forwarding                    https://95ff-103-5-140-188.ngrok-free.app -> http://localhost:8080

Connections                   ttl     opn     rt1     rt5     p50     p90
                              0       0       0.00    0.00    0.00    0.00
```

# URL
``` https://95ff-103-5-140-188.ngrok-free.app ```