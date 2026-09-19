[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:4d22691cc07d555e -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# MyWorld_of_Tanks-Videos

一个已归档的个人收藏仓库，存放着 2019 年 7 月至 8 月录制的 63 个《坦克世界》对局录像文件（.wotreplay），没有任何源代码、清单文件或可运行的构建。

[![License](https://img.shields.io/github/license/anyingiit/MyWorld_of_Tanks-Videos)](LICENSE)

[报告问题](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">开始使用</a></li>
    <li><a href="#usage">用法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

MyWorld_of_Tanks-Videos 是 anyingiit 的个人收藏仓库，存放 Wargaming 出品的《坦克世界》对局录像，保存格式是游戏客户端自带的 `.wotreplay` 格式，而不是视频文件。仓库共有 63 个录像文件：其中 61 个位于根目录，录制时间在 2019 年 7 月 24 日至 8 月 9 日之间；另外 2 个是其中较晚两场对局的重复副本，被放进了一个中文名意为"精彩录像"的子文件夹中。每个文件名都记录了录制时间戳、参战的国家与载具（例如 `japan-J25_Type_4`、`sweden-S17_EMIL_1952_E2`、`china-Ch01_Type59` 和 `usa-A17_M37`）以及对战地图，但仓库本身不含任何源代码、软件包清单或构建配置——GitHub 上该仓库已被标记为归档，播放录像也必须依赖《坦克世界》客户端本身。

计划中的内容，见 [open issues](https://github.com/anyingiit/MyWorld_of_Tanks-Videos/issues)。

## 开始使用

### 环境要求

- [《坦克世界》](https://worldoftanks.eu) 游戏客户端（或与之兼容的第三方录像查看器），因为 `.wotreplay` 文件只能通过客户端自带的回放引擎播放
- 除此之外别无所需：本仓库没有任何软件包清单，也没有任何构建配置

### 安装

没有构建步骤，也没有任何需要编译的内容。克隆仓库即可得到录像文件的本地副本：

```sh
git clone https://github.com/anyingiit/MyWorld_of_Tanks-Videos.git
cd MyWorld_of_Tanks-Videos
```

## 用法

仓库里的每一个文件都是一个 `.wotreplay` 录像；用《坦克世界》客户端播放其中一个，例如：

```sh
20190724_1955_japan-J25_Type_4_05_prohorovka.wotreplay
```

《坦克世界》安装后会自动将 `.wotreplay` 扩展名与客户端关联，因此双击某个文件（或者在启动游戏前把它放进客户端自带的 `replays/` 文件夹）即可在客户端的回放界面中打开它。本仓库不提供其他查看器、转换工具或导出步骤；由于录像年代较早，如果游戏数据自 2019 年以来发生了较大变化，个别录像可能无法完全正常回放。

## 参与贡献

欢迎参与。[CONTRIBUTING.md](CONTRIBUTING.md) 说明如何提交 issue 或 pull request，[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 说明对所有参与者的行为要求。

请不要在公开的 issue 或 pull request 中报告安全问题。[SECURITY.md](SECURITY.md) 说明了私下报告的方式。

## 许可证

以 MIT 许可证分发。详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/MyWorld_of_Tanks-Videos](https://github.com/anyingiit/MyWorld_of_Tanks-Videos)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
