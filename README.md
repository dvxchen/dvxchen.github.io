<!-- 每次保存自动刷新目录，快捷键Ctrl+Shift+P → Create Table of Contents -->
- [文档标题：测试与自动化技术手册](#文档标题测试与自动化技术手册)
  - [1 项目概述](#1-项目概述)
    - [1.1 项目简介](#11-项目简介)
    - [1.2 文档规范](#12-文档规范)
  - [2 常用代码示例](#2-常用代码示例)
    - [2.1 JS/Node 示例](#21-jsnode-示例)


# 文档标题：测试与自动化技术手册
## 1 项目概述
### 1.1 项目简介
本文档用于整理 **UI5自动化(wdi5)、AI Agent测试、排错记录**，托管于GitHub Pages，全程使用标准Markdown语法渲染，无乱码、排版稳定。

### 1.2 文档规范
1. 所有文件统一 UTF-8 编码；
2. 图片统一存放路径：`assets/img/xxx.png`；
3. 代码块标注语言，便于高亮识别；
4. 标题层级严格：# > ## > ###，不越级。

![示例图](/assets/img/token.png)


## 2 常用代码示例
### 2.1 JS/Node 示例
```javascript
// ESM 环境 __dirname 兼容代码
import { fileURLToPath } from 'url';
import { dirname, join } from 'path';
const __filename = fileURLToPath(import.meta.url);
const __dirname = dirname(__filename);

// 路径拼接
const configPath = join(__dirname, "wdio.conf.js");
console.log("配置路径：", configPath);

| 左对齐（默认） | 居中对齐 |   右对齐 |
| :------------- | :------: | -------: |
| 文本靠左       | 文本居中 | 文本靠右 |
| abc            |   123    |      999 |

| 参数名  | 类型   | 是否必填 | 说明                 |
| :------ | :----- | :------: | :------------------- |
| url     | string |    是    | 接口请求地址         |
| timeout | number |    否    | 超时时间，默认3000ms |
| token   | string |    否    | 身份鉴权令牌         |

| 内容             |
| ---------------- |
| 第一行<br>第二行 |

