## MyChatRoom
A chat room demo based on Socket, include server and client, written in C#. <br /><br />

### 介绍
一个用C#编写的基于Socket的Windows版聊天室，包括服务端和客户端。当服务端启动服务后，客户端可以连接到服务端，给服务端发送数据，服务端可以接收数据；
服务端可以给客户端发送数据，客户端接收；
可以有多个客户端同时连接服务端，服务端可以群发消息到每个客户端。

### 主要知识点
- 委托，委托原理
- 文件读操作，文件写操作
- 单线程和多线程
- 简单多线程实现
- 套接字简介
- IP和端口
- 服务端和客户端循环接收对方数据，双向通信
- 发送文字，发送文件(自定义消息协议)
- 异常处理

### 服务端启动：
![server][1]  
<br />

### 客户端连接到服务端后可以和服务端传输数据和文件:
![client][2]

## 下载
[Download link 可执行文件][3]


  [1]: http://images.cnitblog.com/blog/282019/201401/082306325661.png
  [2]: http://images.cnitblog.com/blog/282019/201401/082310340664.png
  [3]: http://files.cnblogs.com/fanyong/MyChatRoom.rar