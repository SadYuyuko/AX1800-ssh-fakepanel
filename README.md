# AX1800-ssh-fakepanel  
适用于小米AX1800或其他长得像路由器的东西，在原版固件下仅用ssh展示温度内存等信息  

1. ssh连接。如果用winscp把[panel](https://raw.githubusercontent.com/SadYuyuko/AX1800-ssh-fakepanel/main/panel)放入`/usr/bin/`则跳到第4步  
2. 执行`vi /usr/bin/panel`，粘贴[panel](https://raw.githubusercontent.com/SadYuyuko/AX1800-ssh-fakepanel/main/panel)内容
3. `ESC`，`:wq`保存退出  
4. 执行`chmod +x /usr/bin/panel`  
5. 执行`panel`，效果如图所示  
  <img width="400" height="500" alt="1" src="https://github.com/user-attachments/assets/cd257d47-e3c6-4519-98a1-eb0c9b8c01a3" />  

删除：执行`rm /usr/bin/panel`  
ssh连接后自动显示：执行`echo "/usr/bin/panel" >> /etc/profile`  
