## run

`node app.js > out.txt`

另启动一个终端

`ab -n5000 -c100 http://127.0.0.1:3000/`

统计各个worker进程接受到的请求数量

`ag 46176 | wc -l`