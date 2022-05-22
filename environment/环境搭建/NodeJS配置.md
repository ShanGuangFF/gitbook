# Node 多版本安装

## 一、多版本安装

下载 [nvm](https://github.com/coreybutler/nvm-windows/releases)

选择解压版：[nvm-noinstall.zip](https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-noinstall.zip)

卸载已存在的 node.js

配置环境变量

![image-20220523000552545](C:\Users\LiJiangFeng\AppData\Roaming\Typora\typora-user-images\image-20220523000552545.png)

![image-20220523000705415](C:\Users\LiJiangFeng\AppData\Roaming\Typora\typora-user-images\image-20220523000705415.png)

Settings 文件配置

```shell
root: D:\Environment\nvmAndNode\nvm 
path: D:\Environment\nvmAndNode\node 
arch: 64 
proxy: none
node_mirror: https://npm.taobao.org/mirrors/node/
npm_mirror: https://npm.taobao.org/mirrors/npm/
```

NVM 使用

```shell
# 安装 node
#nvm install <version>
nvm install 12.18.2
nvm user 12.18.2
nvm ls
```

![image-20220523001347105](C:\Users\LiJiangFeng\AppData\Roaming\Typora\typora-user-images\image-20220523001347105.png)

