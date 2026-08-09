# typora-linen-export

`linen-export` 是 Typora 的"导出主题"——PDF / HTML 导出专用主题，与阅读主题 `linen-paper` 配套。

## 安装

1. 复制 `linen-export.css` 到 Typora 主题目录：
   - macOS：`~/Library/Application Support/abnerworks.Typora/themes/`
2. 重启 Typora
3. 在导出对话框选 `linen-export` 作为导出主题

## 字体依赖

主题通过 `@font-face` + CDN 加载以下字体，本地已装时优先命中本地：

- 正文：**Songti SC**（macOS 系统自带）
- 标题 / 强调：**Source Han Serif SC**（Google Fonts `Noto Serif SC`）
- 代码：**Fira Code Nerd Font**（jsDelivr 镜像 Nerd Fonts GitHub）

## 适用范围

- PDF 导出（A4 / 30mm 边距 / 页码 / h1 强制新页）
- HTML 导出（自动跟随）

## 配套主题

- 阅读主题：[typora-linen-paper](https://github.com/Linen9/typora-linen-paper)

## License

MIT
