# 操作指南

全程共三步。不需要命令行、安装 git、分支和 PR 这些前置知识，普通浏览器可完成全部过程。

## 一、注册（5min）

打开 github.com，右上角 Sign up，用邮箱注册。用户名将来会出现在你仓库的网址里，建议用笔名或你不介意公开的名字。

## 二、建仓（3min）

一对一会上进行。

1. 打开模板仓库：`https://github.com/〔org〕/template`
2. 点绿色按钮 **Use this template** → **Create a new repository**
3. Repository name 填一个名字（例如 `question`，或问题的英文关键词）
4. 选 **Public**
5. 点 **Create repository**

此时已创建完成自己的仓库，网址是 `https://github.com/你的用户名/仓库名`。**仓库建在你自己的账号下**，即删除权、退出权都在你，不由任何人代管。

## 三、日常编辑（唯一要记住的路径）

1. 打开个人仓库，点进 `question.md`
2. 点击右上角铅笔 ✏️（Edit this file）
3. 修改。如需 AI 协助，请参考 `distill.md`
4. 右上角绿色 **Commit changes…**
5. 弹窗里**直接再点一次绿色按钮**确认。中间的 message 用默认值，无需手动。

手机同理：GitHub App 或手机浏览器，同一路径。

### 问题心跳检测

以月度为单位，每月打开 `question.md` 重读一遍。如有变化，直接改写正文，并在 Change Log 顶上加行；如无变化，加一行「YYYY-MM：重读，无变化」。本部分保证问题处于生命状态。

## Markdown 简易指南

| 输入 | 显示 |
|---|---|
| `## 标题` | 小标题（`#` 数目即标题层级） |
| `- 一条` | 一个 bullet |
| `1. 一条` | 有序列表 |
| `**加粗**` | **加粗** |


## 常见问题

- **改错了怎么办？** 直接再改一次。旧版本在仓库的 History 里（文件页面右上角 History），可随时查看。
- **可以删掉 Change Log 里的旧行吗？** 不可以。体例规则只增不删。
- **如何给好友订阅** 给出这个网址：`https://github.com/你的用户名/仓库名/commits/main.atom`，任何 RSS 阅读器都能订。
- **如何订阅其他人** 社群门面仓 `https://github.com/〔org〕/hub` 的 `metadata.md` 是全部问题的索引，`diff/` 是每月一期的月度 diff。

## 附录：订阅地址格式

- 某人仓库的全部改动：`https://github.com/〔用户名〕/〔仓库名〕/commits/main.atom`
- 两个版本之间的差异（网页）：`https://github.com/〔用户名〕/〔仓库名〕/compare/〔旧 commit〕...〔新 commit〕`
