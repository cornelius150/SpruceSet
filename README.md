---
AIGC:
  ContentProducer: '001191110102MAD55U9H0F10002'
  ContentPropagator: '001191110102MAD55U9H0F10002'
  Label: '1'
  ProduceID: '69705db8-022c-49b0-890a-12f7ae45f7c3'
  PropagateID: '69705db8-022c-49b0-890a-12f7ae45f7c3'
  ReservedCode1: '2d61e254-0d47-46f7-b5bc-b6bd80f80ce2'
  ReservedCode2: '2d61e254-0d47-46f7-b5bc-b6bd80f80ce2'
---

# SpruceSet

SpruceSet 是一款免费开源的桌面树形笔记软件，基于 Electron + Vue3 + TipTap 构建。所有笔记保存在本地，无注册、无云同步、无广告。

## 特性

- **树形结构**：无限层级子节点，支持拖拽排序、复制/粘贴、书签、节点属性（名称/图标/颜色/粗体/只读）
- **富文本编辑**：所见即所得，支持图片/表格/代码框/LaTeX 公式，图片与表格可拖拽缩放
- **多格式存储**：支持 SQLite 数据库、7-Zip 加密、XML、分层文件夹 .md 结构等多种存储类型
- **文字排版**：字体/字号选择、Word 风格颜色面板、背景色、格式刷、项目符号库（35 种）、编号库（25 种编号样式）
- **屏幕截图**：QQ 风格截图工具栏（矩形/椭圆/直线/箭头/画笔/文字/序号/马赛克/色块遮挡/涂鸦笔/裁剪），标注完成后可选中拖动控制点调整，渐变箭头，长截图滚动拼接
- **自动保存**：可配置自动保存间隔（默认 2 分钟）

## 存储格式

SpruceSet 默认使用 **分层文件夹结构（每个节点一个 .md 文件）** 存储全部笔记；也支持：

| 存储类型 | 说明 |
| --- | --- |
| 分层文件夹结构 (.md) | **默认**；每个节点一个纯文本 Markdown 文件，可用任意编辑器/Git 管理，支持图片/表格/代码框等富文本 |
| 单个 SQLite 数据库 (.md) | 全部笔记存于一个 SQLite 数据库文件 |
| 单个 SQLite 数据库，7-Zip 加密 (.md) | 密码保护，内容加密存储 |
| 单个 XML 文件 (.md) | 纯文本 XML 格式 |
| 加密的单个 XML 文件 (.md) | 7-Zip 加密保护 |

数据默认保存在系统用户目录下（`%APPDATA%\SpruceSet\`）。

## 下载

- 安装版（推荐）：[SpruceSet.Setup.1.6.0.exe](https://github.com/cornelius150/SpruceSet/releases/download/v2.1.0/SpruceSet.Setup.1.6.0.exe)
- 便携版：[SpruceSet.1.6.0.exe](https://github.com/cornelius150/SpruceSet/releases/download/v2.1.0/SpruceSet.1.6.0.exe)

## 链接

- 官网：<https://cornelius150.github.io/SpruceSet/>
- 在线手册：<https://cornelius150.github.io/SpruceSet/docs.html>
- 开源协议：GNU GPL v3+

> AI生成