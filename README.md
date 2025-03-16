# MainNote
Main Study Note

1.  //下载FastGithub Linux版安装包到opt目录
# arm版本需要下载 fastgithub_linux-arm64.zip
    
2.  wget -c -O /opt/fastgithub_linux-x64.zip https://gitee.com/chcrazy/FastGithub/releases/download/2.1.4/fastgithub_linux-x64.zip
    

4.  //解压
    
5.  unzip -d /opt /opt/fastgithub_linux-x64.zip
 

10. //删除FastGithub Linux版安装包
    
11. rm /opt/fastgithub_linux-x64.zip
    

13. //切换目录
    
14. cd /opt/fastgithub_linux-x64
    

16. //以systemd服务安装并启动，即开机自启动

18. sudo /opt/fastgithub_linux-x64/fastgithub start
    
19. //卸载服务
    
20. sudo /opt/fastgithub_linux-x64/fastgithub stop
    

22. //手动启动
    
23. sudo /opt/fastgithub_linux-x64/fastgithub
