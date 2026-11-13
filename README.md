# Doc2X AI文档翻译解析插件（Zotero 9/10/11）

英文名：**doc2x-ai-translate**（1.1.12 及更早版本名为 doc2x-parse）

在 Zotero 里直接用 [Doc2X](https://doc2x.noedgeai.com) 处理论文 PDF：

- **保留排版翻译**：生成版式与原文一致的译文 PDF
- **双语对照**：原文与译文对照阅读
- **解析 / 翻译为 Markdown 笔记**：结果保存回论文条目
- 支持多选 PDF 顺序批量处理

## 安装

1. 在 [Releases](https://github.com/NoEdgeAI/Doc2XZoteroPlugin9/releases/latest) 下载 `doc2x-ai-translate.xpi`（不要解压）。
2. 打开 Zotero「工具 → 插件」，点齿轮菜单选「从文件安装插件」，选中 `.xpi`；也可以直接把文件拖进插件窗口。
3. 首次使用需要登录：在 Zotero 工具栏点 Doc2X 图标，选「浏览器登录」，在浏览器里登录 [Doc2X](https://doc2x.noedgeai.com)（没有账号可以直接注册）后点「连接」即可，不需要安装客户端。电脑上已经登录了 Doc2X 客户端的，插件会直接读取它的登录。

已安装的插件会自动更新。

| Zotero 版本 | 安装包 |
| --- | --- |
| 9、10、11 | 本仓库 |
| 7、8 | [NoEdgeAI/Doc2XZoteroPlugin](https://github.com/NoEdgeAI/Doc2XZoteroPlugin/releases/latest) |

本仓库只发布安装包和自动更新信息（`release` 标签下的 `update.json`）。

---

**doc2x-ai-translate** translates and parses PDFs in Zotero with Doc2X AI: layout-preserving translation, bilingual output, or Markdown notes. Download `doc2x-ai-translate.xpi` from [Releases](https://github.com/NoEdgeAI/Doc2XZoteroPlugin9/releases/latest) and install it via *Tools → Plugins → ⚙ → Install Plugin From File*. For Zotero 7/8, use [NoEdgeAI/Doc2XZoteroPlugin](https://github.com/NoEdgeAI/Doc2XZoteroPlugin/releases/latest).
