
### 仓库需设置为 public，[token](https://github.com/settings/tokens) 权限也要开放，具体要哪些权限尚未测试，先全勾了😏
### 图片链接暴露 github id，谨慎使用

### [picgo-core 配置](https://picgo.github.io/PicGo-Core-Doc/zh/guide/config.html)

1. 系统需要安装 node.js
2. 直接在 typora 下载安装 picgo-core
3. 在 C:\Users\xxx\AppData\Roaming\Typora\picgo\win64 打开cmd，自动生成配置命令 picgo set uploader
4. 手动配置也👌
![image-20210814132756228](https://raw.githubusercontent.com/ysinx/tuchuang/main/image-20210814132756228.png)
6. PicGo目前不支持github上传同名文件，会报错
7. 遇到的 bug，命令行配置，图床选中 github，配置文件却写入 smms，导致报错，手动修正可解决
