# 组件初始资源


## 初始化数据
在`init/resources/component/info`文件夹下编写json文件，放置组件的实体配置信息，支持一个文件存放多个组件
```json
[
  {},
  {}
]
```
## 初始化分组
编写`init/resources/component/group.json`，分组也将自动初始化
```json
[
  {
    "id": "demoGroup",
    "name": "示例分组"
  }
]
```
## 初始化初始缩略图
在`init/thumbnail`文件夹下放置缩略图文件，将组件实体配置信息的`thumbnailUrl`字段更换为图片文件名称

