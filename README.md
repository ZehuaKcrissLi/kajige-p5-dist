# 咔鸡哥 P5/P6 团本训练服 · 中国大陆加速分发镜像

这个仓库只做一件事：给中国大陆的玩家提供一条能跑满带宽的下载线路。

官方站点 <https://kaji-training.kcriss.dev> 走境外线路，大陆访问经常很慢甚至打不开。
所以这里保留了一份**路径完全一致**的副本：安装包和资源包作为 Release 附件，
发布清单与增量更新数据放在仓库里。安装器内部也内置了同一批加速线路，主站连不上时会
自动换源续传。

每个文件的 SHA-256 都固定写在安装器里，更新清单还有 Ed25519 签名。换源只影响下载速度，
不可能影响安装内容。

## 一、下载安装器

到 [最新 Release](https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/latest) 页面，
或者直接用下面的加速线路（三条给的是同一个文件，哪条能打开用哪条）：

| 系统 | 线路一 | 线路二 | 线路三 |
| --- | --- | --- | --- |
| Windows 10/11 | [下载](https://gh-proxy.com/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Windows-v1.4.13-p6-cn2-20260929.zip) | [下载](https://gh.llkk.cc/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Windows-v1.4.13-p6-cn2-20260929.zip) | [下载](https://ghfast.top/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Windows-v1.4.13-p6-cn2-20260929.zip) |
| Apple Silicon Mac | [下载](https://gh-proxy.com/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Mac-v1.4.13-p6-x87-cn2-20260929.dmg) | [下载](https://gh.llkk.cc/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Mac-v1.4.13-p6-x87-cn2-20260929.dmg) | [下载](https://ghfast.top/https://github.com/ZehuaKcrissLi/kajige-p5-dist/releases/download/v1.4.13-p6-cn2-20260929/Kajige-P5-Raid-Trainer-Mac-v1.4.13-p6-x87-cn2-20260929.dmg) |

Mac 也可以在“终端”里直接敲一行，脚本会自己挑可用线路、校验并打开安装器：

```sh
curl -fsSL https://gh-proxy.com/https://raw.githubusercontent.com/ZehuaKcrissLi/kajige-p5-dist/main/install-mac.sh | zsh
```

## 二、17 GB 简中客户端

安装器会自己完成这一步，正常情况下不需要手动操作。只有取种失败时才需要手动补：

- 磁力链接（推荐，大陆 BT 速度通常最好）：
  `magnet:?xt=urn:btih:1cd47a5a9d2450faca2dbbb632e80a00f566cfcc`
- 种子文件：[Kajige-3.3.5a-zhCN-12340.torrent](Kajige-3.3.5a-zhCN-12340.torrent)
- 百度网盘客户端本体，提取码 `1qcs`：<https://pan.baidu.com/s/1NFdBat5W5r-6xfEKdUUofA?pwd=1qcs>
- 百度网盘 12340 主程序，提取码 `ryry`：<https://pan.baidu.com/s/1UOqihWs5pbFvDJC4YQeJag?pwd=ryry>

## 三、这里都有什么

| 路径 | 说明 |
| --- | --- |
| `release.json` | 发布清单，含全部文件大小、SHA-256 与镜像配置 |
| `SHA256SUMS.txt` | 站点根目录全部文件的校验值 |
| `install-mac.sh` | macOS 一行命令安装脚本 |
| `client-sources-v1.json`(`.sig`) | 已签名的客户端下载源清单 |
| `updates/stable/manifest-v2.json`(`.sig`) | Ed25519 签名的增量更新清单 |
| `updates/blobs/` | 按内容寻址的增量更新数据块 |
| Release 附件 | Windows/macOS 安装包、资源包、种子文件 |

仓库里的路径和官方站点一一对应，所以任意 GitHub 加速代理都能直接当镜像用，
例如把 `https://kaji-training.kcriss.dev/updates/stable/manifest-v2.json` 换成
`https://gh-proxy.com/https://raw.githubusercontent.com/ZehuaKcrissLi/kajige-p5-dist/main/updates/stable/manifest-v2.json`。

## 说明

《魔兽世界》商标与游戏内容归其权利人所有。本仓库不包含游戏本体，
基础客户端由安装器从清单中标明的第三方来源取得。

