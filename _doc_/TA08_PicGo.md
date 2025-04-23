# 连享会 PicGo 图床配置


- 简要版：[图床工具的使用：PicGo 介绍](https://www.jianshu.com/p/9d91355e8418)
- 完整版：[Markdown图片神器：PicGo-让你爱上笔记与分享](https://www.lianxh.cn/details/769.html)


### 1. 下载-安装 PicGo

> **重要提示**：请不要下载最新版本的 PicGo 软件，要用下面的版本。

- 坚果云：<https://www.jianguoyun.com/p/DXhBsWkQtKiFCBixj9oD> 
  - 版本：PicGo-Setup-2.3.0-beta.4
  - Update: `2021/1/11 10:45`
  - 解压后按提示安装即可。
- 最新版下载地址：<https://github.com/Molunerfinn/PicGo/releases>

### 2. 配置图床 (依次填入)

打开 PicGo，点击左侧「**图床设置**」下来菜单，选择「**阿里云OSS**」，填入如下信息：

  - **设定 KeyID：** LTAI4Fv321ae7Sm9okgZLfMz
  - **设定 KeySecret：** `请联系连老师索要`
  - **设定存储空间名 (bucket)：** fig-lianxh  
  - **确认存储区域：** oss-cn-shenzhen   
  - **指定存储路径：** 不填
  - **设定自定义域名：** 不填

>**特别提示：** 复制上述设定信息时，<font color=red>切记不要复制 **多余的空格** </font>，否则会导致设定失败。

![PicGo-阿里云图床配](https://fig-lianxh.oss-cn-shenzhen.aliyuncs.com/PicGo-阿里云图床配置.png)


### 3. 上传图片

- **本地图片**：采用点击或拖拽方式上传完图片后，PicGo 会自动生成 Markdown 格式的图片链接：一份自动存于剪切板，另一份显示在屏幕右下角。我们只需到 Markdown 编辑窗口中，按下快捷键「**Ctrl+V**」即可贴入图片链接地址。
- **剪切板图片**：通过截图等方式得到的图片 (已经自动保存在了剪切板上)，可以直接点击图中右底角【剪切板图片上传】按钮上传图片 (有时候需要点击两次才能正确上传，可以点击左边栏的【相册】按钮查看是否成功上传)。

![](https://fig-lianxh.oss-cn-shenzhen.aliyuncs.com/PicGo-上传图片.png)

### 4. 其他说明

- 点击左边栏【相册】按钮，可以查看已经上传的图片，并从图片下方的第一个菜单复制图片链接； 
- 点击【PicGo设置】可设定快捷键和各种参数，较少使用。