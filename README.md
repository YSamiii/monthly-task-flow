# 月度任务追踪 iPhone 安装版（PWA）

这是一个可以添加到 iPhone 主屏幕的网页 app。

## 文件说明

- `index.html`：主程序文件，必须放在网站最外层。
- `manifest.webmanifest`：PWA 安装信息。
- `sw.js`：离线缓存文件。
- `icon-192.png` / `icon-512.png` / `apple-touch-icon.png`：手机主屏幕图标。

## 安装到 iPhone

1. 把整个文件夹上传到 GitHub Pages、Netlify、Vercel 或其他 HTTPS 网站空间。
2. 用 iPhone 的 Safari 打开该网址。
3. 点 Safari 底部分享按钮。
4. 选择“添加到主屏幕”。
5. 之后就可以像普通 app 一样从主屏幕打开。

## 注意

- 直接在电脑本地双击 `index.html` 可以使用，但不能完整触发 iPhone 的 PWA 安装和离线缓存。
- 数据保存在浏览器本地。换手机、换浏览器或清理 Safari 数据前，请先在 app 内导出 JSON 备份。
- 这不是 App Store 原生 app，不需要 Apple Developer 账号，也不需要 Mac。
