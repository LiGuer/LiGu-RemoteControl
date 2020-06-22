# LiGu-RemoteControl  
## Introduction  
* This is a Remote Control Program
* Function:  
  1. [dir "url"]指令: 查询文件列表  
    ·1-1. "url": 目标文件夹路径  
    ·1-2. 未填"url"时,默认"D:\\"  
  2. [file "url"]指令: 文件传输  
    ·2-1. "url": 目标文件路径  
    ·2-2. "url"错误时，会报错，不影响程序  
  3. [quit]指令: 断开连接  
    ·3-1.程序不易关闭，断开连接不影响程序，可多次重连。  
  4. [request]指令: 询问  
  5. [screen]指令: 屏幕截图  
  6. 控件台窗口最小化，避免视觉干扰。  
  7. 套接端口号为57953，位数较高。  

## Daily
[2020年3月5日]  
【/* 冰河远程监控系统】  
功能:  
1. [dir "url"]指令: 查询文件列表  
    ·1-1. "url": 目标文件夹路径  
    ·1-2. 未填"url"时,默认"D:\\"  
2. [file "url"]指令: 文件传输  
     ·2-1. "url": 目标文件路径  
     ·2-2. "url"错误时，会报错，不影响程序  
3. [quit]指令: 断开连接  
     ·3-1.程序不易关闭，断开连接不影响程序，可多次重连。  
4. [request]指令: 询问  
5. [screen]指令: 屏幕截图  
6. 控件台窗口最小化，避免视觉干扰。  
7. 套接端口号为57953，位数较高。   
  
·主控端(客户端)可用"网络调试助手"代替完成。    
![test image](https://github.com/LiGuer/LiGu-RemoteControl/blob/master/img/img03.png)
  
[2020年3月4日17:00]  
【/* 冰河远程监控系统】  
功能:  
1. [dir]指令: 查询文件列表  
2. [file]指令: 文件传输  
3. [quit]指令: 断开连接  
4. [request]指令: 询问  
5. [screen]指令: 屏幕截图  
6. 控件台窗口最小化，避免被发现。  
7. 程序不易关闭，断开连接不影响程序，可多次重连。    

[2019年12月22日01:33]  
【/* 冰河远程监控系统】服务器端50%  
1. 屏幕截取功能完成，文件传输完成。  
2. 只是winsocket2.h库函数的使用，没有技术含量。  
3. 文件、截图接收后，暂时只能显示Ascii码，  
    不能保存为文件，因为还没写客户端程序。  
4. 客户端的界面程序编写，又是一件路漫漫其修远兮的事【头秃】  
![test image](https://github.com/LiGuer/LiGu-RemoteControl/blob/master/img/img01.png)
![test image](https://github.com/LiGuer/LiGu-RemoteControl/blob/master/img/img02.png)
