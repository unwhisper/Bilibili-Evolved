<div align="center"><img id="Bilibili-Evolved" width="500" alt="Bilibili Evolved" src="images\bilibili-evolved-wide-color.svg"></div>
<br>
<div align="center">

「 强大的哔哩哔哩增强脚本 」

</div>


[📦 安装](#安装) / [Install](install-tutorial.en-US.md) / [インストール](install-tutorial.ja-JP.md)

[⚙ 设置](#设置)

[📚 功能](#功能)

[👻 兼容性](#兼容性)

[🐛 版本历史与更新日志](https://github.com/the1812/Bilibili-Evolved/releases)

[📖 相关文档](https://github.com/the1812/Bilibili-Evolved/wiki)

[❤ 捐助](donate.md)

# 安装
需要浏览器拥有[Tampermonkey](https://tampermonkey.net/)插件.

点击名称即可安装👇 (点了之后需要一点时间下载)

| [正式版](https://github.com/the1812/Bilibili-Evolved/raw/master/bilibili-evolved.user.js) | [预览版](https://github.com/the1812/Bilibili-Evolved/raw/preview/bilibili-evolved.preview.user.js) | [离线版](https://github.com/the1812/Bilibili-Evolved/raw/master/bilibili-evolved.offline.user.js) | [预览离线版](https://github.com/the1812/Bilibili-Evolved/raw/preview/bilibili-evolved.preview-offline.user.js) |
| ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 正式发布的版本, 最稳定, 更新频率较低.                                                     | 新增内容测试的地方, 更新频率高, 但功能不稳定.                                                      | 内置所有依赖项, 体积较大, 更新频率高于正式版.                                                     | 兼备预览版和离线版的特点.                                                                                      |

> **非离线版安装后运行可能会提示"脚本试图访问跨域资源", 请选择"始终允许".**

> 某些破坏性的大更新会使旧版脚本**完全**无法工作, 请及时检查更新.

# 设置
脚本启用后, 在网页左侧中央会有一个齿轮图标, 点击即可打开设置. 默认只启用了一部分功能, 您可以根据需要自由调整设置.

设置项的说明见[功能](#功能)一节, 在网页中通过鼠标停留在某一项也可以查看简要说明.

**绝大部分设置保存后, 需要刷新网页才能生效. 仅有一些样式设置可以立即生效.**

<img alt="设置" height="500" src="images/compressed/gui-settings.jpg">

# 功能
大部分功能可通过设置面板开启, 有一些功能会以`附加功能`的形式生效, 或者是可以在`附加功能`做进一步设置. `附加功能`可从网页左侧中央的功能按钮进入.

可以在[功能列表](features.md)页中查看每项功能的详细说明.

# 兼容性

## 脚本管理器

### [Tampermonkey](https://tampermonkey.net/) / [Violentmonkey](https://violentmonkey.github.io/)
完全兼容, 但在较旧的浏览器中 Violentmonkey 可能无法运行此脚本.

### [Greasemonkey](https://www.greasespot.net/)
可以安装, 但是由于 Greasemonkey 4 只允许脚本在页面完全加载后运行, 样式相关功能体验会比较糟糕, 比如打开夜间模式后每个页面在完全加载之前都是亮色的. 所以还是强烈建议您使用上述的两种脚本管理器.

## 浏览器

支持**最新版** Chrome, Edge (Chromium 内核), Firefox, Safari, 不保证脚本能在["套壳类浏览器"](https://www.jianshu.com/p/67d790a8f221)或者较长时间没更新的浏览器中完美运行.

UWP 版 Edge 已经不再支持了(就是 Windows 10 自带的那个), 请使用以上列出的浏览器, 或换用 [Chromium 内核的 Edge](https://microsoftedgeinsider.com/).

另外, Chromium 内核的 Edge 可以通过特殊手段启用中文界面, 网上搜一下就有, 或者也可以参考这篇 [Gist](https://gist.github.com/the1812/bd5c3edabd61b03696428fcfde53d74f). (需要梯子)

# 关于源码
虽然本项目的源代码是公开的, 但是我并不推荐您花太多时间阅读这些代码. 因为这是我的第一个JavaScript项目, 它包含了从我初学JavaScript到如今形成一定风格以来写下的各种代码(各种祖传代码), 不同的几个模块可能风格差异会很大, 像是早期DOM操作经常使用jQuery到后期转向原生API和Vue, 4空格缩进变成2空格缩进等等. 一些比较复杂的模块里也是放飞自我.

所以, 如果您希望通过阅读源码来学习知识的话, 建议去看看那些更专业更成熟的项目.

------

**喜欢的话就点个⭐Star吧(°∀°)ﾉ**

**或者也可以考虑[捐助](donate.md)支持一下哦(｀・ω・´)**

支付宝

<img alt="支付宝" src="images/compressed/alipay.jpg" height="200">

微信

<img alt="微信" src="images/compressed/wechat.jpg" height="200">
