# docs

本项目为 netless 白板官方文档站，由 CI 自动部署在[文档站](https://developer.netless.link)。

目前使用 docusaurus，满足以下需求：

1. 顶部大分类：iOS，Android，JavaScript 以及其他内容
2. 不同分类，独立导航，自定义顺序
3. 当前文章目录TOC
4. 相对地址跳转检查
5. 语法块切换

未满足以下需求：

1. 搜索
2. 多语言
3. 术语超链接，降低输入相对地址的复杂程度，全站同一术语，自动使用同一超链接
4. 自动生成导航目录，而不是手动编写（可能会与自定义排列顺序冲突）