# GEEBAR之轉生

一个基于Persona 5 Royal风格的视觉效果展示网页。

## 项目简介

本项目是一个的单页面应用，灵感来源于Persona 5 Royal游戏中的角色COOP满好感度动画和UI设计。

## 功能特点

- 🔄 **设备方向** - 在移动设备上需要进行横屏，提供最佳视觉效果

## 项目结构

```
├── favicon\           # 网站图标文件
├── img\               # 图片资源
│   └── bg.png         # 背景图片
├── index.html         # 主页面文件
├── sound\             # 音频资源
│   └── chain-rankup.MP3  # 链条音效
├── svg\               # SVG图形资源
│   ├── s-chain*.svg   # 链条相关SVG
│   ├── s-card*.svg    # 卡片相关SVG
│   ├── s-star.svg     # 星星图标
│   ├── s-*-b.svg  #暗色版本图标
│   └── *.svg          # 其他UI元素
```

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式和动画效果
- **JavaScript** - 交互逻辑和动画控制
- **SVG** - 矢量图形资源

## 注意事项

- **移动设备使用**：在移动设备上，请旋转设备至横屏模式以获得最佳体验（有页面提示😋）
- **浏览器支持**：建议使用现代浏览器如Chrome、Firefox、Safari或Edge以获得最佳效果
- **性能优化**：页面包含大量动画和SVG资源，在低端设备上可能需要更长的加载时间

## 开发说明

### 自定义配置

- 如需修改背景图片，请替换 `img/bg.png` 文件
- 如需修改音效，请替换 `sound/chain-rankup.MP3` 文件
- 如需修改SVG图标，请替换 `svg/` 目录下的文件（主要是arcade相关的图标需要文字修改）
- 动画时间和效果可在 `index.html` 中的JavaScript代码部分调整

### 资源加载

项目使用资源预加载机制，确保所有资源在显示主内容前加载完成。

## 许可证

本项目仅供学习和展示使用，基于游戏Persona 5 Royal的视觉风格创作。

---

*Persona 5 Royal是Atlus Co., Ltd.的注册商标。本项目与Atlus Co., Ltd.无关。*
