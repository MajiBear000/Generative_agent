# Generative_agent
Django 使用细节， 启动sever时指定port用以下代码：
```
python manager.py runsever [PORT]
```
使用虚拟机转发端口，需要指定ip为0.0.0.0。否则默认为127.0.0.1为localhost，转发时远程获取不了本地ip
```
python manager.py runsever 0.0.0.0:[PORT]
```
