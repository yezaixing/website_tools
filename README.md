# 图片工具箱 (Image Toolbox)

免费在线图片处理工具集。纯前端处理，无需上传，即时完成，保护隐私。

## 功能

| 工具 | 说明 |
|------|------|
| 格式转换 | JPG ↔ PNG ↔ WebP |
| 图片压缩 | 质量滑块控制 |
| 裁剪/缩放 | 常用尺寸 + 自定义 |
| 旋转/翻转 | 90°/180°/270° + 自定义角度 |
| 灰度处理 | 灰度强度调节 |
| 亮度/对比度 | 独立调节 |
| 添加水印 | 文字水印 + 位置控制 |
| 模糊效果 | 模糊强度调节 |
| 圆角处理 | 圆角半径调节 |
| 图片拼接 | 多图拼贴成网格 |

## 项目结构

```
/
├── index.html           # 主页面
├── ads.txt              # Google AdSense 验证
├── assets/
│   ├── css/
│   │   └── style.css    # 样式
│   └── js/
│       └── app.js       # 核心逻辑
└── README.md
```

## 技术栈

- 原生 HTML/CSS/JavaScript
- Canvas API 图片处理
- 纯前端处理，图片不上传服务器
- 国际化支持（中/英）

## 本地运行

```bash
python -m http.server 8080
```

访问 `http://localhost:8080`

## 部署

使用 Cloudflare Pages 或 Vercel 免费托管。