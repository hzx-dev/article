# DeepSeek 本地运行指南 Pro

## 写在前面

这是 DeepSeek 本地运行指南的续集。上一集在此处查看：[Luogu](https://www.luogu.com.cn/article/3qzn63pi) [Github Pages (我的个人博客网站)](https://hzx-dev.github.io/article/DeepSeek%20%E6%9C%AC%E5%9C%B0%E8%BF%90%E8%A1%8C%E6%8C%87%E5%8D%97.html)

因为有人~~（其实是我）~~嫌在终端看 DeepSeek 的输出导致只能看到纯文本，所以本片文章将介绍一个更加高级的 DeepSeek 本地运行方法。

## 步骤

> 本指南作者使用的电脑配置为：
>
> Mac Mini M4
> 
> 可以流畅使用 8B 模型。

1. 安装 LM Studio

   打开 [LM Studio 的官网 （单击此处打开）](https://lmstudio.ai/)，下载适合您操作系统的版本。（在本指南编写时，使用的是最新的 0.3.9）
   
   下载完成之后打开安装包会自动安装 ~~（是的，它甚至不给你选安装路径）~~。
   
2. 下载模型

   安装好 LM Studio 后打开，会见到以下界面：

   ![LM Studio Launch UI](https://cdn.luogu.com.cn/upload/image_hosting/weapj3o4.png)

   > 选读：将 LM Studio 的语言改为中文。
   >
   > 按下界面右下角的设置按钮，选择以下选项：App Settings -> Language -> 展开选项 -> 简体中文（Beta）。
   >
   > 设置完成后即可。（这是一项 Beta 功能！）

   不过我们现在并没有任何模型，我们需要下载一个，下载模型有两个方法。
   
   - 使用 LM Studio 

