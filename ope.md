
# 要求
## git 和 Markdown 
  *  github有一个关于寒假学习的分支，要求上传寒假你写的所有代码
  *  练习写几篇blog  

## Linux 
   1. 学习Linux的[操作](#操作)
   2. 对Linux系统有一个整体的认知
   3. 必会ssh 服务，DHCP | DNS | FTP | samba | nfs | Apache | Nginx | 邮件服务 | Mysql 任意一个 学会编译安装！
   
### 操作
   * 基本操作
   * 和挂载相关的知识[mount]
   * 软件源配置相关知识 [yum apt-get 对应的相关文件]
   * Linux下的网络配置，网络排查
   * linux下的日志查看
   * 系统磁盘【fdisk】，系统文件系统【mkfs】，用户配置文件[profile bashrc]等相关的知识。
     * /etc下基本的文件是做什么的 
     * (centos下)文件： fstab | inittab | init.d/ | sysconfig/ 等都是作甚的！  
     
### 任务
  自己学习搭建一个服务，了解它的配置文件("eg: Webserver Dhcp Dns nfs samba vncserver ntp ")
   
## 网络工程
   1. 交换机的概念
   2. vlan的概念，交换的概念，三层交换的概念
   3. 交换机端口的各个模式和vlan之间的关系
   4. 生成树的概念，Stp,Rstp,Mstp，了解生成树的基本流程
   
   **看完后必须用模拟器模拟真实的使用环境。**
   
#参考资料
## Linux 
 
 * [鸟哥](http://vbird.dic.ksu.edu.tw/) 尤其是《鸟哥私房菜》的 5-23 章值得一看
 * [Linux 工具快速教程](http://linuxtools-rst.readthedocs.org/zh_CN/latest/index.html)
 * 网络博客

## 网络
* 推荐网站:
   * [华三官网](http://www.h3c.com.cn/ "华三官网")　自行搜索技术白皮书  
   * [华为官方学习](http://support.huawei.com/learning/NavigationAction!createNavi#navi[id]=TRAIN "") 学习HCNA相关知识
   * [鸿鹄论坛](http://bbs.hh010.com/ "网络工程大咖")
* 推荐资料：（华三的路由交换【四卷】 1[基础],2[交换],3[路由]　卷）
* 推荐模拟器：　
    *  [华三云模拟器](http://www.h3c.com.cn/Service/Software_Download/Other_Product/H3C_Cloud_Lab/HCL/HCL/201410/842486_30005_0.htm "h3c couldlab")
    *  [华为ENSP](http://support.huawei.com/enterprise/toolsinfo?idAbsPath=0602_ROOT&pid=0602_ROOT&show=showVersionDetail&contentId=TL1000000015&offeringid=9017384&versionid=21605923 "huawei　ensp") 
   


## 扩展 
### 运维
* 自己搭建一个网站的环境LAMP
    * 放一个自己喜欢的开源网站（博客站(typecho ,wordpress 等等)）　 
    * 可以自己搭建DNS服务器解析自己的网站
    * 添加记录解析baidu.com到你的网站的ip
   
### 网络工程　
* 路由器的概念
   * 静态路由的配置
   * 基本的路由协议　rip   ospf
   *  各种路由协议，路由表生成的方式

