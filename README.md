# 作息助手官网 - 图片素材说明

## 需要准备的图片

请将以下图片放入 `assets/images/` 目录：

| 文件名 | 尺寸 | 说明 |
|--------|------|------|
| `icon.png` | 512x512 | App 图标（透明背景） |
| `og-image.png` | 1200x630 | 社交分享封面图 |
| `app-preview.png` | 320x640 | App 预览图（手机截图） |
| `screenshot-1.png` | 300x600 | 截图1 - 主界面 |
| `screenshot-2.png` | 300x600 | 截图2 - 添加日程 |
| `screenshot-3.png` | 300x600 | 截图3 - 提醒设置 |

## 快速开始

1. 从 Android 设备截图
2. 裁剪为推荐尺寸
3. 放入 `assets/images/` 目录
4. 部署到 Netlify

## 部署到 Netlify

方法一：拖拽上传
- 访问 [app.netlify.com/drop](https://app.netlify.com/drop)
- 拖拽整个 `website` 文件夹
- 完成！

方法二：Git 部署
- 将 website 文件夹推送到 GitHub 仓库
- 在 Netlify 连接仓库并部署

## SEO 验证

1. 本地测试：`python -m http.server 8080`（在 website 目录内运行）
2. Google Search Console 提交 sitemap
3. 结构化数据测试：https://search.google.com/test/rich-results