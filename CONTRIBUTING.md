# 合作指南

以下为合作，欢迎提issue、pr补充修改。

## 所需能力

- 良好的英语阅读能力
- 了解RST(ReStructureText)基本语法
- 良好的团队合作能力

## 贡献要求

**每周至少一篇**

## 怎么开始？

需使用python3

pull项目

```shell
git clone git@github.com:DonaldDai/Bokeh-CN_new.git
```

安装相关依赖

```shell
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple doc8 docutils sphinx-autobuild sphinx bokeh colorcet networkx
```

`-i`表示使用清华镜像源

下载示例数据(python 交互式命令行中)

```python
>>> import bokeh
>>> bokeh.sampledata.download()
```

构建文档html(在`/[root]/sphinx`路径下)

```shell
make html
```

在浏览器中打开`/[root]/sphinx/build/html/index.html`可查看翻译后文档最终效果

## 推荐工具

- vscode
- vscode 插件：[reStructuredText](<https://marketplace.visualstudio.com/items?itemName=lextudio.restructuredtext>)

