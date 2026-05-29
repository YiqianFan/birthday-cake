# 生日蛋糕 - 夜空许愿

一个交互式生日蛋糕网页，梦幻夜空主题。拖动吹灭蜡烛，看着祝福语在屏幕底部浮现。

## 功能

- **拖动吹灭** — 按住蛋糕区域拖动即可吹灭蜡烛，支持触屏和鼠标
- **三阶段熄灭** — 火焰挣扎加速闪烁 → 急剧收缩消失 → Canvas 绘制的烟雾缓缓升腾
- **Canvas 粒子系统** — 火星、流星、烟花、彩纸、萤火虫，800 粒子对象池复用，稳定 60fps
- **夜空氛围** — 弯月、流云、极光背景、闪烁星空
- **祝福语** — 吹灭后在屏幕底部逐条淡入淡出
- **重新点燃** — 按按钮可再次点燃蜡烛

## 快速开始

无需构建，直接浏览器打开 `index.html`：

```
git clone https://github.com/YiqianFan/birthday-cake.git
cd birthday-cake
open index.html
```

在线体验：https://yiqianfan.github.io/birthday-cake/

## 技术栈

- 纯 HTML + CSS + JavaScript，零依赖
- Canvas 2D 粒子渲染
- CSS 动画处理静态装饰（星星、月亮、云、烛焰）
- 对象池模式复用粒子，避免动画期间 DOM 创建/销毁

## 许可证

MIT
