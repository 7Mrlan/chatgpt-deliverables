# 星阅 · 原版蓝色 Logo 高清矢量复刻 · v1.1

**这是修复清晰度问题的新交付，不是改版品牌设计。**

旧版 v1 使用约 **452×452** 的展示截图，插值放大到 1024×1024，并未增加真实细节。本版重新用曲线路径绘制纸页与折叠关系，所有大图直接从 SVG 渲染，因此边缘清楚，支持任意输出分辨率。

- [直接下载完整 Android ZIP](XingYue-Android-HiRes-v1.1.zip)（包含 33 个文件）
- [SVG 矢量主文件](XingYue_Master_Vector.svg)
- [2048px 高清 PNG](XingYue_Icon_2048.png)
- [1024px PNG](XingYue_Icon_1024.png)
- [原截图与矢量版清晰度对比](Original_vs_Vector.png)

ZIP 内含透明前景、深色环境版本、512px/1024px/2048px 文件，以及 Android `mipmap-` 多密度和 `mipmap-anydpi-v26/` 自适应图标配置。

### Android 集成
将 ZIP 中 `XingYue-HiRes-v1.1/03_android/res/` 的子目录合并复制到 Android 模块的 `app/src/main/res/`（保留其他资源，备份现有图标）。在 `AndroidManifest.xml` 的 `application` 中配置：

```xml
android:icon="@mipmap/ic_launcher"
android:roundIcon="@mipmap/ic_launcher_round"
```

**精度说明**：SVG 是依照你认可的原版重新描绘的矢量稿，并非 AI 展示图的原生矢量工程文件，所以曲线、渐变细节可能与截图稍有不同。若优先追求原截图的逐像素外观，请使用 v1 作为视觉参考；若用于实际 App，优先使用 v1.1。
