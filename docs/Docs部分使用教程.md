---
title : Docs部分使用教程
---

## 1. 添加一份新的Docs
Docusaurus的Docs部分使用动态路由自动配置Docs，若需要新建一个Docs页面，只需要在project/docs目录下新增一个`.mdx`或`.md`文件即可。
## 2. 添加一个新的Docs目录
若需要新建一个Docs目录，只需要在project/docs目录下新增一个目录，并在该目录下新增一个`.mdx`或`.md`文件即可。Docusaurus会自动将该目录作为一个Docs目录。
且在此目录下的`.index.mdx`或`.index.md`文件会作为该目录的首页。
## 3.修改Docs文档的元数据信息
若需要修改Docs文档的元数据信息，只需要在该文档的开头添加一个YAML格式的元数据块即可。Docusaurus会自动解析该元数据块，并将其作为该文档的元数据信息。
例如此文档的元数据如下
```md
---
title : Docs部分使用教程
---
```