# webserver
用C++实现的高性能web服务器
参考：《linux高性能服务器编程》

➜  webbench-1.5 ./webbench -c 1000 -t 60 http://172.20.10.3:1316/ 
Webbench - Simple Web Benchmark 1.5
Copyright (c) Radim Kolar 1997-2004, GPL Open Source Software.

Benchmarking: GET http://172.20.10.3:1316/
1000 clients, running 60 sec.

Speed=267192 pages/min, 10024091 bytes/sec.
Requests: 267192 susceed, 0 failed.


通过Webbench测试
最大客户端数量为1000，持续时间60秒
速度267192页面/分钟    10024091 字节/秒
请求数量267192次，全部成功，0失败
