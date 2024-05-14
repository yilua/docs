## 忽略副标题 <!-- {docsify-ignore} -->
当设置了 subMaxLevel 时，默认情况下每个标题都会自动添加到目录中。如果你想忽略特定的标题，可以给它添加 <!-- {docsify-ignore} --> 。
```markdown
# Getting Started

## Header <!-- {docsify-ignore} -->

该标题不会出现在侧边栏的目录中。
```
要忽略特定页面上的所有标题，你可以在页面的第一个标题上使用 <!-- {docsify-ignore-all} --> 。
```markdown
# Getting Started <!-- {docsify-ignore-all} -->

## Header

该标题不会出现在侧边栏的目录中。
```
在使用时， <!-- {docsify-ignore} --> 和 <!-- {docsify-ignore-all} --> 都不会在页面上呈现。
## 二级菜单栏测试02
> 笔记1