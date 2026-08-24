# 小宇宙 MP3 导出工具

> **Export Xiaoyuzhou audio as MP3 for devices that cannot play M4A.**

高驰 PACE 3 只能读取 MP3，而小宇宙提供的音频通常是 M4A。手动下载后再找转换网站，步骤多，也会把个人收听习惯暴露给第三方服务。

这个小工具把「下载 + 转换」压成一次操作，仓库同时保留 Chrome 扩展和更轻量的用户脚本实现。

## 仓库内容

```text
manifest.json     Chrome 扩展配置
background.js     后台任务
content.js        页面内容处理
popup.*           扩展弹窗
script            轻量用户脚本
```

## 边界

- 仅用于个人合法获取和离线收听；
- 页面结构变化可能导致脚本失效；
- 音频版权与使用范围由用户自行遵守。

这是一个很小的项目，但它代表我的默认 Builder 路径：**先遇到真实麻烦，再把重复步骤做成工具。**
