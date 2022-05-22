# Gitbook 安装配置

## 一、利用 npm 安装 gitbook

```shell
npm install gitbook-cli g
```

> npm 的包安装分为本地安装（local）、全局安装（global）两种
>
> 本地安装：
>
> npm install xxx 安装到命令行所在目录的 node_module 目录
>
> 全局安装：
>
> npm install xxx -g 安装到 \AppData\Roaming\npm\node_modules 目录

gitbook-cli是一个实用程序，可在同一系统上安装和使用多个版本的gitbook。 它将自动安装所需版本的gitbook。安装好后可查看版本号：

```shell
gitbook -V
```

![image-20220523002321158](C:\Users\LiJiangFeng\AppData\Roaming\Typora\typora-user-images\image-20220523002321158.png)

## 二、创建

gitbook 创建模板书

```shell
# 参数为创建的目录，默认为当前目录下
gitbook init [./directory]
```

## 三、输出

```shell
# 执行命令可以进行预览 参数为指定输出静态网站的目录，默认会在当前目录下新建一个子目录 _book
gitbbok serve ./{book_name}
# gitbook 创建的书可以导出为电子书，pdf、epub、mobi格式
gitbook pdf ././mybook.pdf
gitbook epub ././mybook.epub
gitbook mobi ././mybook.mobi
```

其中，最后一个参数表示输出文件的文件名，可省略，默认输出为当前目录下的book文件。
再前面一个参数表示gitbook所在的目录。