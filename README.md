# 远程配置
## 一、config.gradle
所有 build.gradle 文件，都依赖此远程配置，统一管理。

## 二、maven_publish_plugin.gradle
需要发布 aar 的 module 依赖此远程配置，实现快速上传 aar 到 maven
