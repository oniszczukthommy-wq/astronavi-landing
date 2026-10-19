# 天文通 · 官网落地页（Astronavi Landing）

深色星空电影风的单文件产品宣传页。在线预览：https://hcn4pc1ewda5.doubaoapps.com/app/app_17etd2u5kmk

## 模块
黑洞穿越开场 → Hero 粒子标题「有天象，看天文通」→ 双向跑马灯 → 十二宫与二十八星宿自动逐点连线 → 四大功能（观星指数 / 星图 AR / 光污染地图 / 空间站过境）→ 可拖拽太阳系 3D → 930 亿光年大标题 → 今夜数据面板 → 动态月相 → 下载 CTA → 发信号到比邻星。

## 技术栈
- Three.js r149：分层视差星野、流星、太阳系、程序化月相、UnrealBloom
- GSAP 3.12 + ScrollTrigger 滚动叙事
- 原生 JS，无构建；图片 base64 内嵌；prefers-reduced-motion 降级
- Noto Serif SC 大标题 / Noto Sans SC 正文

## 说明
完整成品为单个自包含 HTML（图片内嵌后约 5MB）。本仓库 `index.html` 为在线预览跳转入口；完整源码请从在线部署包获取或在本地构建目录查看。
