---
layout: default
title: Xiletrade
lang: zh-CN
description: Path Of Exile 游戏的价格检查器和辅助工具
strings:
  maintained: 项目由
  generated: 此页面由
  download: 下载
  repository: 在 GitHub 上查看
  footer: 免费服务需要持续维护才能正常运行。
  issue: 并使用
  latest: 最新版本
  support: 捐赠
---
{% include screenshot.md %}
## 只需一个动作即可检查您的商品价格

*立即找到最佳价格范围。*  
*即时设置行为。*  
*游戏更流畅，交易更快！*  

## {% include youtube.svg %} ： [定价](https://youtu.be/4mP3uOsr8oc) - [批量](https://youtu.be/6yuLZXTho-A) - [设置](https://youtu.be/libdIjrNM-8)<br>

以少量 CPU 资源高效运行。  
最大使用 ***250 MB 的 RAM***，没有内存分配峰值。  
***没有在后台写入数据***。  

* * *

# {% include setup.svg %} 主要功能：

- 使用定义的快捷键 ***CTRL+D*** *默认情况下*，快速**检查所有商品的价格**。
- 使用 ***CTRL+R*** 快速打开 **设置** 以修改价格检查行为。
- 通过 POE 进行 **批量物品交换** 以进行快速私下交易。
- **附加组件** 帮助定价物品并检索有关相关物品的更多信息。
	- 与 **poe.prices**、**poeninja**、**poewiki** 和 **poedb** 软链接。
- 检查 **新更新** 并在启动时刷新自定义/官方 **过滤器**。
- 遵守 [第三方政策](https://www.pathofexile.com/developer/docs#policy) 中的 **单一操作** 规则的功能：
	- 通过发送带有关联 **热键** 的预定义消息与 **聊天控制台** 交互
例如快速前往 **藏身处** 或 **交易** 操作。
	- 根据需要将 **鼠标滚轮** 与 **左键单击** 绑定。
- **正则表达式管理器**实用程序。
	- 管理已定义的**正则表达式**列表。
	- 自动粘贴到高亮栏中。  

<img align="center" src="https://github.com/user-attachments/assets/1a3229fe-9f61-4c18-b4de-98e2ee026ace">
<br>

## {% include install.svg %} 安装和设置：

1. [**下载**]({{ site.github.download_directory_url }}{{ site.github.latest_version }}/{{ site.github.archive_file}})最新版本并**提取** **`.7zip`**存档到所需目录。
Xiletrade 是一个**便携式应用程序**，启动时不会安装任何其他内容。
2. **右键单击**系统托盘图标以配置或关闭程序。
3. 在启动或设置窗口下选择所需的**游戏版本**、**语言**和**联赛**。
4. **将鼠标悬停**在每个功能上，直到出现工具提示以获得深入解释。  
<br>
<img src="https://github.com/user-attachments/assets/2aa8b83a-9144-4b56-8d79-1808aac0d486">
<br>

* * *
> # 工作原理：
>
> 以**窗口**或**无边框全屏**模式运行游戏，以便正常工作。
> 确保 Xiletrade **语言**和**联盟**与相应的游戏设置相匹配。
> 一旦 Xiletrade 启动并设置完毕，您现在可以按照以下步骤**检查价格**：
>   1. 将鼠标**放在游戏中的某个物品**上，然后按 ***CTRL+D*** *（默认）*
>   2. 它会从游戏中复制**物品信息描述**并打开 Xiletrade 窗口。
>   3. 如果搜索返回匹配结果，窗口将显示**估计价格**。
>   4. 显示的价格基于**官方交易网站** [PoE 1](https://www.pathofexile.com/trade/search/) 和 [PoE 2](https://www.pathofexile.com/trade2/search/poe2/)。
<br>

### {% include tools.svg %} 可自定义行为：

* **将主窗口**拖到屏幕上的任意位置。
* 按**当前**项目值或层级范围内的**最小值**进行搜索。
* 使用**鼠标滚轮**更改数值（最小/最大）
* 按住**CTRL**或**SHIFT**键可显示小数值。
* 调整**不透明度**并在窗口失去焦点时**自动关闭**。
* 单击主窗口的**左上角**图标。
* 在地图（配置文件中）中**突出显示****昂贵**和**危险模组**。
* **自动粘贴**来自外部网站的游戏内私聊交易。

```
旨在遵守官方交易网站设定的规则
以避免因数据恢复受限和随时间推移的请求而造成的滥用。
```