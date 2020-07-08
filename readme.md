# 基于模板的大作业

## 使用说明：
1. Easyconnect 连接校园网；
2. 使用shell工具登录个人账户到实验室计算机
ip: `10.168.20.166`, ssh port:`22`
3. 配置编译环境
    - 临时环境：`export PATH=/usr/local/texlive/2019/bin/x86_64-linux:$PATH`
    - 永久环境：添加一行`export PATH=/usr/local/texlivee/2019/bin/x86_64-linux:$PATH` 到 `~/.bashrc`的末尾；  
               执行`source ~/.bashrc`生效。
4. `git clone https://github.com/nTnZone/signalOptimal.git` 
5. `cd signalOptimal && chmod +x artratex.sh`
6. `./artratex.sh xa`
7. `cd Tmp`，在Tmp目录下利用sftp工具取回`main.pdf`
