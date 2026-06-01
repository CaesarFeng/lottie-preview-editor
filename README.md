# Lottie 预览编辑器

一个本地可用的 Lottie JSON 预览和编辑工具。

## 功能

- 上传、拖入或粘贴 Lottie JSON 文件
- 预览动画并控制播放、重播和进度
- 查看图层并拖拽调整顺序
- 编辑填充、描边和渐变颜色
- 设置预览背景、播放速度和循环次数
- 保存修改后的 JSON
- 导出 GIF

## 使用

直接打开 `index.html` 可以预览和保存 JSON。

如果要导出 GIF，请用本地静态服务打开，避免浏览器在 `file://` 下拦截 GIF Worker：

```bash
python3 -m http.server 8123
```

然后访问：

```text
http://127.0.0.1:8123/index.html
```

