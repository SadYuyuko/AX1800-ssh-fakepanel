# AX1800-ssh-fakepanel  
适用于小米AX1800或其他长得像路由器的东西，在原版系统下不依赖插件仅用ssh展示温度内存等信息  

1. ssh连接  
2. 执行`vi /usr/bin/panel`  
3. 粘贴[面板](https://raw.githubusercontent.com/SadYuyuko/AX1800-ssh-fakepanel/main/panel.sh)内容
4. `ESC`，`:wq`保存退出  
5. 执行`chmod +x /usr/bin/panel`  
6. 执行`panel`，效果应该如图所示  
  <img width="437" height="500" alt="1" src="https://github.com/user-attachments/assets/5da5a3ab-7b33-49f5-bce8-75e3ce3e10ca" />  
  
删除：执行`rm /usr/bin/panel`  
