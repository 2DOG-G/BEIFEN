# WARP全教程
----
>[!note|style:flat|iconVisibility:hidden|labelVisibility:hidden]
> 最后更新时间:2023年7月14日
----

> |缺点|优点|
> |----|----|
> |可能**无法隐藏自己的真实IP**|0成本|
> |**无法访问封锁国内IP的网站**,例如CHATGPT/Netflix等|几乎无限的流量|
> ||无速度限制|

> ## 1. 前期准备
> - 访问网址: [https://1.1.1.1](https://1.1.1.1);
> - 所需文件下载地址: [https://pan.2dog.dog/OD_02/01-RuanJian/001-FanQiang](https://pan.2dog.dog/OD_02/01-RuanJian/001-FanQiang);
> - 安装软件;
> - **安卓版本有很多限制, 建议使用第三方软件**;

> ## 2. 优选IP
> - ![Alt text](/img/image-1.png ':size=49%') ![Alt text](/img/image.png ':size=49%')
> - 如遇到始终**正在连接/速度慢**等情况,需要更改连接IP;
> - 点击**优选IP**后(需关闭所有代理软件以获得正确结果)(运行时长在**3-5分钟**,如发生未响应无需理会),会在根目录生成**result.csv**,打开后复制靠前的IP:端口号,点击**设置IP**即可;

> ## 3. 获取几乎无限的流量
> ### 3.1 方式1:Telegram机器人
>   - Telegram机器人:[https://t.me/generatewarpplusbot](https://t.me/generatewarpplusbot)
>   - 根据提示获取WARP+的KEY;
>   - ![Alt text](img/image-2.png ':size=44%') ![Alt text](/img/image-3.png ':size=54%')
> ---------
> ### 3.2 方式2:免费注册Cloudflare团队账户
>   - 访问并注册账户:[https://www.cloudflare.com/](https://www.cloudflare.com/)
>   - 点击侧边栏**Zero Trust**注册团队账户;
>   - 直到添加信用卡这一步,关闭网页,重新访问**Zero Trust**,即可跳过添加信用卡;
>   - 点击侧边栏**My Team** → **Devices**,填入你的邮箱的后缀,例如@qq.com;
>   - ![Alt text](/img/image-2.png ':size=44%') ![Alt text](/img/image-4.png ':size=54%')
>   - 根据提示填写刚才注册的团队前缀,填写邮箱,填写验证码,然后**允许网页打开程序**即可;

> ## 4. 使用第三方软件
> - 有了优选IP后,可使用第三方软件进行固定的线路连接,获得更快的访问速度;
> - **基于WARP+进行操作**;
> - WARP本质上是**基于WireGuard的代理软件**,所有带有WireGuard协议的代理软件均可使用;
> - WireGuard客户端下载:[https://www.wireguard.com/install/](https://www.wireguard.com/install/) 


> ### 4.1 获取WireGuard配置
> - 下载:[https://github.com/ViRb3/wgcf/releases](https://github.com/ViRb3/wgcf/releases),(选择windows_amd64)
> - 在文件所在目录,在地址栏输入**CMD**,回车;
> - 输入wgcf,按tab自动补全,空格,```register```;
> - 打开生成的**wgcf-account.toml**,将**license_key**的值更改为获取的WARP+KEY,保存;
> - 输入wgcf,按tab自动补全,空格,```update```;
> - 输入wgcf,按tab自动补全,空格,```generate```;
> - 打开生成的**wgcf-profile.conf**,将**Endpoint**的值更改为任意**优选IP**,保存;
> - 打开**WireGuard**,新建隧道→选择**wgcf-profile.conf**,连接;

> ### 4.2 其他带有WireGuard协议的软件
> - iOS上的Shadowrocket
> ![Alt text](/img/image-5.png)
> -------
> - Nekoray:Windows/Android
> - Clash