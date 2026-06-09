---
sidebar_position: 2
title: 如何开启光影？
---

# 如何开启光影？

开启光影需要搭配对应的渲染模组/插件，目前有两种主流方案：

## 方案一：Sodium + Iris Shaders

适用于 Fabric/Quilt 加载器：

- **Sodium**（或 Rubidium / Embeddium）— 性能优化渲染模组
- **Iris Shaders**（或 Oculus）— 光影加载模组

1. 安装 Sodium 和 Iris Shaders 模组
2. 启动游戏 → **选项 → 光影设置**
3. 选择已导入的光影包
4. 调整光影参数后开始游戏

## 方案二：Optifine

适用于 Forge 加载器或独立安装：

1. 安装 Optifine（高清修复）
2. 启动游戏 → **选项 → 视频设置 → 光影**
3. 选择光影包并应用

:::warning 兼容性
- Optifine 在高版本中与模组兼容性较差，不推荐与大量模组同时使用
- 推荐在 1.16.5 及以下版本使用 Optifine，1.17+ 推荐 Sodium + Iris 方案
- 光影兼容性请参考 [光影兼容矩阵](/docs/mobileglues/ShaderSupportMatrix)
:::
