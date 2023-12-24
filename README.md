# 哪吒自定义主题

[演示地址](https://tz.euser.cf)

## 使用方法
### 如果安装面板时选用docker方式安装,步骤如下
1、将```template```里面的```文件```放到服务端```/opt/nezha/dashboard/theme-custom/template```目录里面

2、重启哪吒面板服务
```
    1）docker ps
    2）docker restart 上一步中哪吒的id
```

3、登录哪吒面板后台，设置===>主题==>选择Custom(local)

4、将css.txt里面的CSS样式代码复制到哪吒面板后台的“自定义代码”文本框里

5、保存

### 如果安装面板时选用独立方式安装,步骤如下
1、将```template```里面的```文件```放到服务端```/opt/nezha/dashboard/resource/template/theme-custom```目录里面

2、重启哪吒面板服务
```
    systemctl restart nezha-dashboard
```

3、登录哪吒面板后台，设置===>主题==>选择Custom(local)

4、将css.txt里面的CSS样式代码复制到哪吒面板后台的“自定义代码”文本框里

5、保存

## 新增及修改内容

1、内存、硬盘少于1GB时以MB显示, 多于1GB时精确到小数点后2位

2、卡片中在线时间后增加TCP（T）、UDP（U）连接数和进程数（P）信息

3、卡片增加: 流量、cpu、内存、虚拟内存、硬盘、负载详细信息

4、修改背景图片、Logo、版权、Favicon（可自行在设置中的css代码内修改）

5、NaN% ==> 未设置

6、信息栏 ==> 绿色:内存； 蓝色:虚拟内存； 紫色:硬盘

7、CPU图标 ==> 绿色:物理核心；蓝色:虚拟核心





