# 咔鸡哥 P6 团本训练服 · 中国大陆下载安装

80 级太阳井、奥杜尔 14 场首领机制训练服。GM 可单人进本反复练习，团长可编排机器人
站位、仇恨和 P4/P5/P6 备战配装。

官方站点在境外，大陆访问经常很慢甚至打不开，所以这里放了一份**内容完全相同**的加速
副本。安装器内部也用同一批线路，全程自动换源，每个文件都按固定 SHA-256 校验。

## 快速开始

先看下面的「新手完整指引」，尤其是第 0 步。

| 系统 | 线路一 | 线路二 | 线路三 |
| --- | --- | --- | --- |
| Windows 10/11 | [下载](https://gh-proxy.com/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Windows-v1.4.14-p6-20261001.zip) | [下载](https://gh.llkk.cc/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Windows-v1.4.14-p6-20261001.zip) | [下载](https://ghfast.top/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Windows-v1.4.14-p6-20261001.zip) |
| Apple Silicon Mac | [下载](https://gh-proxy.com/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Mac-v1.4.14.dmg) | [下载](https://gh.llkk.cc/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Mac-v1.4.14.dmg) | [下载](https://ghfast.top/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.14-p6-20261001/Kajige-P6-Raid-Trainer-Mac-v1.4.14.dmg) |

三条线路给的是同一个文件，哪条能打开就用哪条。Windows 约 14 MB，Mac 约 30 MB。
还有两条备用：`https://cdn.gh-proxy.com/` 和 `https://ghproxy.net/`，用法是把它们
接在 [完整文件列表](https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/tag/v1.4.14-p6-20261001) 里的下载地址前面。

Mac 也可以在“终端”里直接敲一行，脚本会自己挑可用线路、校验并打开安装器：

```sh
curl -fsSL https://gh-proxy.com/https://raw.githubusercontent.com/ZehuaKcrissLi/kajige-p5-dist/main/install-mac.sh | zsh
```

## 新手完整指引

### 第 0 步 · 先确认两件事

- 硬盘至少留出 **40 GB** 空闲空间。游戏本体约 17 GB，解压过程还要额外空间。
- 向咔鸡哥要一个**账号和密码**。训练服没有网页注册，账号只能由管理员创建；
  没有账号的话，装好了也只能停在登录界面。

### 第 1 步 · 下载安装器

用上面表格里的线路，几秒就下完。这个小包不含游戏本体。

### 第 2 步 · 运行安装器

**Windows**：解压 ZIP，双击 `KajigeP5Installer.exe`，点“一键高速下载安装”。
系统可能提示未知发布者，选“更多信息 → 仍要运行”。

**Apple Silicon Mac**：打开 DMG，把里面两个 App 拖到“应用程序”。第一次打开要
**右键点图标再选“打开”**，否则 Gatekeeper 会拦住。然后打开
“咔鸡哥P6训练服安装器”，点“一键高速下载安装”。Mac 不需要 CrossOver 或
Parallels 序列号，安装器会自动配好免费的 Wine x87 运行时。

### 第 3 步 · 等它自己装完

安装器会自动下载 17 GB 简中客户端、中文 UI、插件和训练功能，不需要你选择 BT、
网盘还是备用源。这是唯一耗时的一步，按各家宽带一般几十分钟到几小时。

支持断点续传，**中途关掉甚至关机都没关系**，下次打开安装器接着下，不会从头开始。

### 第 4 步 · 以后只开启动器

装完就不再需要安装器了。打开“咔鸡哥P6训练服”启动器，点“更新并启动游戏”。
以后的小更新只下载变化的文件，不会重复下载客户端。

### 第 5 步 · 登录

用管理员给的账号密码登录。服务器地址不用手动填，安装器已经配好。

**玩的过程中不要关掉启动器。** 它在本机提供两个中继端口，关掉游戏会直接掉线。

### 连不上怎么办

按顺序检查：启动器是否还开着 → 电脑能不能正常上网、防火墙有没有拦住启动器 →
启动器上显示的服务器状态。还是不行就在启动器里运行诊断，把结果发给管理员。
诊断结果不含账号密码，可以放心发。

### 一句提醒

服务器在海外，大陆连过去延迟偏高。练机制、看伤害、熟悉流程都没问题，
但手感不如本地服。

## 手动补 17 GB 客户端（一般用不到）

安装器会自己完成这一步。只有在它取种失败时才需要手动下载，再把目录交给安装器校验。

- 磁力链接（大陆 BT 速度通常最好）：
  `magnet:?xt=urn:btih:1cd47a5a9d2450faca2dbbb632e80a00f566cfcc`
- 种子文件：[Kajige-3.3.5a-zhCN-12340.torrent](Kajige-3.3.5a-zhCN-12340.torrent)
- 百度网盘客户端本体，提取码 `1qcs`：<https://pan.baidu.com/s/1NFdBat5W5r-6xfEKdUUofA?pwd=1qcs>
- 百度网盘 12340 主程序，提取码 `ryry`：<https://pan.baidu.com/s/1UOqihWs5pbFvDJC4YQeJag?pwd=ryry>

## 这个仓库里都有什么

| 路径 | 说明 |
| --- | --- |
| `release.json` | 发布清单，含全部文件大小、SHA-256 与镜像配置 |
| `SHA256SUMS.txt` | 站点根目录全部文件的校验值 |
| `install-mac.sh` | macOS 一行命令安装脚本 |
| `client-sources-v1.json`(`.sig`) | 已签名的客户端下载源清单 |
| `updates/stable/manifest-v2.json`(`.sig`) | Ed25519 签名的增量更新清单 |
| `updates/blobs/` | 按内容寻址的增量更新数据块 |
| Release 附件 | Windows/macOS 安装包、资源包、种子文件 |

路径与官方站点 <https://kaji-training.kcriss.dev> 一一对应，所以任意 GitHub 加速代理
都能直接当镜像用。发布清单这类小文件另有一个轻量镜像仓
<https://github.com/ZehuaKcrissLi/kajige-p5-feed>，体积控制在 jsDelivr 的上限内。

## 说明

《魔兽世界》商标与游戏内容归其权利人所有。本仓库不包含游戏本体，
基础客户端由安装器从清单中标明的第三方来源取得。
