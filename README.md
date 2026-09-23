# 奈娜子密码本（Nainazi Passbook）

个人自用的本地密码本桌面程序。基于 [KeePassXC](https://keepassxc.org/) 二次修改，**仅供本人使用，不面向公众分发或提供支持**。

## 重要说明

- **性质**：个人自用 fork / 定制构建，不是官方产品，也不是对 KeePassXC 项目的官方镜像。
- **上游出处**：[KeePassXC](https://github.com/Nainazi/keepassxc)（KeePassXC Team）。本仓库 Release 中的 Windows 可执行文件由其源码定制编译而来。
- **完整源码**：定制改动在 [Nainazi/keepassxc](https://github.com/Nainazi/keepassxc)（`develop` 分支）。本仓库只放介绍与 Release 安装包，不重复托管整棵源码树。
- **许可**：遵循 KeePassXC 的 GPL-2.0-or-later（及第三方组件各自许可）。使用本二进制即表示你了解需遵守相应开源许可；需要源码请到上面的 fork 仓库获取。
- **安全边界**：本地 KDBX 密码库；填充仅由用户触发（Auto-Type 等）；不做静默抓密、不做云同步、不擅自自动提交表单。

## 这个定制版有什么

相对上游，主要面向「密码笔记本」体验：

- 品牌与中文界面：「奈娜子密码本」
- 「奈娜子」主题（淡紫 / 粉 / 奶油）
- 激进核心 UI：隐藏浏览器集成、SSH Agent、KeeShare、报告等非核心入口，精简工具栏与设置页
- 保留：KDBX 开存、条目增删改查与搜索、复制、用户触发的 Auto-Type、锁定、基础密码生成器

## 怎么用

1. 打开本仓库的 [Releases](https://github.com/Nainazi/--/releases)，下载最新的 `nainazi-passbook-win64.zip`
2. 解压到任意目录，运行 `nainazi-passbook.exe`
3. 新建密码库，或打开已有的 `.kdbx` 文件

## 免责

本仓库与 Release **仅作个人存档与自用**。作者不提供对外技术支持，不保证与官方 KeePassXC 行为完全一致。若你需要通用密码管理器，请使用 [官方 KeePassXC](https://keepassxc.org/)。

## 上游致谢

感谢 KeePassXC 团队与所有贡献者。商标与项目名称归其各自权利人所有。
