<div align="center">
    <h1>SpotifyNext</h1>
    <p>让 Spotify 拥有更多可能</p>

[![Github Release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/cc.meteormc.spotifynext?color=green&logo=github)](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases)
[![Release Downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/cc.meteormc.spotifynext/total?color=orange)](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases)
[![Telegram](https://img.shields.io/badge/Join-Telegram-blue.svg?logo=telegram)](https://t.me/+uECDhJ01E1ExZjFh)

[English](README.md) | [简体中文](README_zh.md)
</div>

---

> [!CAUTION]
> 请在使用前仔细阅读免责声明，并确保你已了解相关风险

> [!NOTE]
> 本模块理论支持大部分 Android 设备和 Spotify 客户端版本  
> 但由于 Spotify 的客户端更新频繁，部分功能可能会出现失效或异常  
> 且后续版本不再保证对旧版本客户端的兼容性  

## ✨ 功能列表

<details>
  <summary><strong>更好的全屏歌词</strong></summary>
  <br/>
　提供更加简洁美观全屏歌词界面，支持逐字歌词显示，且所有功能均使用播放器原生接口
</details>

<details>
  <summary><strong>可点击的歌词预览</strong></summary>
  <br/>
　让播放页面中的歌词预览区域变成可打开全屏歌词的点击入口
</details>

<details>
  <summary><strong>启用随机播放开关</strong></summary>
  <br/>
　允许更改随机播放开关，使用户可以自由控制播放状态
</details>

<details>
  <summary><strong>强制显示逐字歌词</strong></summary>
  <br/>
　允许在播放页的歌词预览中显示逐字歌词
</details>

<details>
  <summary><strong>去广告</strong></summary>
  <br/>
　移除客户端中的广告相关内容，并尽可能自动跳过广告曲目。由于 Spotify 的广告逻辑可能由版本和服务端配置共同决定，此功能不承诺能够拦截所有形式的广告
</details>

<details>
  <summary><strong>歌词翻译</strong></summary>
  <br/>
　将当前歌词使用翻译接口自动翻译到指定语言
</details>

<details>
  <summary><strong>更多歌词源</strong></summary>
  <br/>
　为客户端增加额外的歌词来源。当没有歌词数据，或原始歌词的同步等级不满足要求时，模块将根据歌曲名、专辑、艺术家从配置的歌词源中匹配曲目

> 自定义歌词源需要由用户自行搭建维护或使用第三方平台。当接口不可用、响应格式不正确、曲目匹配错误或歌词版权受限时，可能出现歌词错配或同步不准确的情况
>
> 本模块严格按照客户端规范写回数据流，如果您使用了其他不符合规范或未从正确客户端接口获取歌词的模块和插件，出现功能失效的问题，与本模块无关
>
> 目前支持配置以下歌词源
> 1. 网易云音乐
</details>

<details>
  <summary><strong>移除 Premium 按钮</strong></summary>
  <br/>
　移除底部导航栏中的 Premium 界面入口。该功能只隐藏客户端界面中的按钮，不会改变账号类型、订阅状态或 Premium 权益。
</details>

<details>
  <summary><strong>解除限制</strong></summary>
  <br/>
　解除一些播放器限制，例如无法上一首、无法拖动进度条等
</details>

## 🚀 使用方法

1. 从 [Releases](https://github.com/Xposed-Modules-Repo/cc.meteormc.spotifynext/releases) 下载并安装最新版本
2. 在你的 Xposed 框架中启用 SpotifyNext，并确保已勾选 Spotify 作用域
3. 重新打开 Spotify
4. 进入 Spotify 侧边栏，打开 **SpotifyNext 设置**，按需启用功能

> [!TIP]
> 修改设置后需要重启 Spotify 客户端才能生效

## 🎯 免责声明

- 本项目与 Spotify 官方及其相关公司没有任何隶属或官方合作关系，也未获得官方的授权、认可、维护或技术支持
- 因使用本项目导致的风险，如软件崩溃、数据丢失、播放异常、账号受限或其他任何直接、间接损失，项目作者不承担任何责任
- 部分功能可能绕过 Spotify 的产品设计、账号权限或服务限制，违反 Spotify 的服务条款、账号规定或当地法律法规，使用者需自行承担由此产生的一切后果
- 本项目不提供任何 Premium 权益，也不会修改 Spotify 账号的订阅状态、支付状态或服务器端权限，客户端变化不代表账号已经获得对应服务资格
- 歌词源、翻译接口和其他网络服务均由第三方提供，使用这些功能可能会将歌曲名称、艺术家、专辑、设备网络信息等数据发送给对应服务；其响应数据可能受到著作权、地区限制或服务条款约束，请确保你有权访问、使用和传播相关内容
- 任何第三方服务的稳定性、准确性、隐私政策、数据处理方式和版权合规性均不由本项目控制
- 继续使用本项目即表示你已阅读、理解并接受以上风险与责任划分