# DeepSeek 本地运行指南

## 写在前面

众所周知，现在 DeepSeek 十分的火爆，官网也~~有一点抽风~~遭受了 DDOS 攻击，API 也无法注册。
![DeepSeek 官网服务器繁忙](https://cdn.luogu.com.cn/upload/image_hosting/x4zdj8op.png)
所以，我们可以使用本地运行来避免这些问题，这也是本文章介绍的内容。So, let's go~

## 部署

> 本指南作者使用的电脑配置为：
>
> CPU：Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz   1.80 GHz
>
> RAM：8.00 GB
>
> GPU：
>
> ![](https://cdn.luogu.com.cn/upload/image_hosting/4qqxabdj.png)
>
> 可以流畅使用 1.5B 模型。

### 安装 Ollama

戳这里的链接下载安装程序：[Windows](https://ollama.com/download/windows)	[Linux](https://ollama.com/download/linux)	 [macOS](https://ollama.com/download/mac)

这里以 Windows 为例，打开安装程序之后点击 Install 就好了。

![Windows Example](https://cdn.luogu.com.cn/upload/image_hosting/bjznllti.png)

安装完成后，可以看到 Ollama 的图标。~~（可爱捏）~~

![](https://cdn.luogu.com.cn/upload/image_hosting/jpwhhnqv.png)

安装完成建议**重启电脑**。

## 运行大模型

打开 [Ollama 官网](https://ollama.com/library/deepseek-r1)，在顶部搜索栏输入 `DeepSeek` ，选择一个要使用的模型。

如果你也需要使用 R1，可以直接点击[这里](https://ollama.com/library/deepseek-r1)。

![](https://cdn.luogu.com.cn/upload/image_hosting/8g4z2x0y.png)

我们这里以 R1 为例，选择搜索结果中的 `deepseek-r1` 点击，进入以下页面。

![](https://cdn.luogu.com.cn/upload/image_hosting/e8da1cwl.png)

接下来我们需要选择模型大小。

![](https://cdn.luogu.com.cn/upload/image_hosting/57hm42uh.png)

> Tips:
>
> 如果不知道如何选择模型的大小，可以按照以下方法选择：
>
> - 按下 `Ctrl` + `Shift` + `Esc`，选择 `性能` 选项卡，找到你的 GPU，查看你的 GPU 内存。![](https://cdn.luogu.com.cn/upload/image_hosting/x5eshg7v.png)
> - 回到 Ollama 的页面，选择**比你显存小**的模型（大了会爆内存！！！）

> Warning:
>
> 只有 671B 的模型才是官网使用的模型！！！其他均为蒸馏模型！！！
>
> 671B 的模型需要多张高端显卡，在没有条件的情况下不要轻易使用！！！不要轻易使用！！！不要轻易使用！！！~~（应该没有 OIer 的电脑有这个配置吧？）~~

选择好模型之后，找到右边的指令，点击右边的复制按钮。

![](https://cdn.luogu.com.cn/upload/image_hosting/66u87av2.png)

复制完成后，按下 `Ctrl` + `X`，选择**管理员终端**打开。~~（ `Win` + `R` CMD 也不是不行 ）~~

然后，粘贴（**终端中使用右键粘贴**）刚刚复制的代码，按下回车即可。

初次使用需要下载模型，**耐心**等进度条跑完。

当出现 `Send a message` 字样时即可与 DeepSeek 对话。

![](https://cdn.luogu.com.cn/upload/image_hosting/j21if4cq.png)

至此，您的本地 DeepSeek 已经配置成功！
