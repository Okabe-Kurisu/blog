本博客使用[`hexo`](https://github.com/hexojs/hexo)搭建，并使用了[`fluid`](https://github.com/fluid-dev/hexo-theme-fluid)主题。此仓库的主要目的为了触发持续集成而存在的，所以没有太多描述（暂时）。

- 增加md语法检查插件

    使用`textlint --fix .\source\_posts\*.md`直接检查+纠正，这一步直接放CICD里吧