# PhotoApp
springboot+vue的照片管理器，管理本地照片，可以上传和搜索。web开发小作业

***项目结构***
***数据库***
建表语句：
```sql
CREATE TABLE photos (  
    id INT AUTO_INCREMENT PRIMARY KEY,  
    url VARCHAR(255) NOT NULL,  
    timestamp DATETIME NOT NULL,  
    location VARCHAR(255)  
);  
```

***后端***
后端使用idea搭建springboot项目
记得将application.yml中的“file:D:/uploads/”改为你想要储存到的本地目录
找到PhotoApplication.java运行项目启动后端

***前端***
使用vue2
安装了axious
```
npm install axios --save
```
终端输入npm run serve启动前端

