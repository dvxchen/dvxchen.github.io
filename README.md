# dvxchen.github.io

# Markdown笔记
## 常用语法
- 加粗：**文字**
- 代码块
```bash
git push


# 使用步骤
1. 在github.com仓库网页依次新建上面4个文件，粘贴对应内容并提交；
2. 进入仓库 `Settings -> Pages`，来源选择`Deploy from a branch`，main分支、根目录`/`，保存；
3. 等待1分钟，访问：`用户名.github.io/仓库名/`。

# 日常新增页面规则
1. 新建`xxx.html`，复制任意一个页面的头部导航模板；
2. 首页导航`<a>`新增一条跳转链接；
3. 提交文件，页面自动更新。

# 优势
1. 永久UTF-8，中文绝不乱码；
2. 全部相对路径，不会出现CSS/页面404；
3. 全程网页编辑，不需要Git、PAT、命令行；
4. 无构建、无MkDocs、无yml配置，永久稳定。
