# 我的知识库（Obsidian Vault）

本地 Markdown 知识库，Git + GitHub 私有仓库同步，Quartz 生成对外文档站。

## 快速开始

1. 安装 [Obsidian](https://obsidian.md/)（Windows 下载安装即可）
2. 「打开文件夹作为库」→ 选择本目录 `vault`
3. 首次打开后按提示**信任并启用社区插件**（pre-installed 插件列表在「设置 → 第三方插件」中启用）
4. 按 `知识库指南.md` 开始记录

## 目录

- `00-收件箱` … `90-模板`：见 `知识库指南.md`
- `.obsidian/`：Obsidian 配置（Git 管理，注意插件本体不入库，用插件市场安装）

## 同步机制

- 本仓库自动每 10 分钟 commit + push（obsidian-git 插件）
- 远程仓库（GitHub 私有）建立后：`git remote add origin git@github.com:<你的账号>/<库名>.git && git push -u origin main`
- 手机端：Obsidian App 打开同一库（GitHub 提交后的内容），安卓可用 MGit / Termux 同步，iOS 可用 Working Copy

## 发布（Quartz 静态站）

见 `../docs/发布部署.md`。
