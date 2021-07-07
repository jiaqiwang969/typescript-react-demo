# TypeScript-React-Demo

一个用TypeScript编写的React演示。

## 演示

一个显示在文本表格中输入的名字的Hello World。

https://maechabin.github.io/typescript-react-demo/

## 演示源代码

- [src/Hello.tsx](https://github.com/maechabin/typescript-react-demo/blob/master/src/Hello.tsx)
- [index.html](https://github.com/maechabin/typescript-react-demo/blob/master/index.html)

##  检查演示。

### 1.下载演示（克隆）。

```
$ git clone git@github.com:maechabin/typescript-react-demo.git typescript-react-demo
```

### 2. 进入你克隆Demo的目录，安装必要的软件包。

``` 
$ cd typescript-react-demo
$ npm install
```

### 3. 打开演示。

```
$ open  /index.html
```

##  修改Demo => 用webpack构建

###  1.在修改完".src/Hello.tsx "后执行以下命令。

``` 
$ npm run build
``` 

####  如果你想通过监控文件来构建webpack

``` 
$ npm run watch
``` 

####  使用HMR时

```
$ npm run server
```

http://localhost:8080 确认

###  2.打开演示

```
$ open /index.html
```
