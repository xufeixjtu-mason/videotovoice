# 📱 视频转音频工具 - 在线版部署指南

## 🎯 目标
将视频转音频工具部署到 **GitHub Pages**，这样你可以：
- 📱 手机随时随地访问使用
- 🌍 在任何有网的设备上使用
- 🔗 拥有自己的专属网址
- 💰 **完全免费**

---

## 🚀 快速部署（5分钟搞定）

### 步骤 1：创建 GitHub 账号
1. 访问 https://github.com
2. 点击 "Sign up" 注册账号（如果已有账号请跳过）

### 步骤 2：创建新仓库
1. 登录 GitHub
2. 点击右上角 `+` 按钮 → "New repository"
3. 填写仓库名称，如：`video-to-audio-tool`
4. 选择 "Public"（公开，免费）
5. 勾选 "Add a README file"
6. 点击 "Create repository"

### 步骤 3：上传文件
1. 在新建的仓库页面，点击 "Add file" → "Upload files"
2. 将 `index.html` 文件拖放到上传区域
3. 点击 "Commit changes"

### 步骤 4：启用 GitHub Pages
1. 在仓库页面，点击 "Settings"（设置）
2. 左侧菜单点击 "Pages"
3. 在 "Source" 部分，选择：
   - Branch: `main`
   - Folder: `/ (root)`
4. 点击 "Save"
5. 等待 1-2 分钟，刷新页面
6. 页面会显示你的网址，如：
   ```
   Your site is live at https://你的用户名.github.io/video-to-audio-tool/
   ```

### 步骤 5：访问使用
1. 复制上面的网址
2. 在手机的浏览器中打开
3. 开始使用！

---

## 📋 包含文件

| 文件 | 说明 |
|------|------|
| **index.html** | 🔥 **网页版主文件（用于部署）** |
| video_to_audio.html | 本地测试版 |
| video_to_audio.py | Python 命令行版 |
| convert.sh | 拖放脚本版 |
| start_server.sh | 本地服务器启动脚本 |

---

## 🛠️ 更新工具

如果后续更新了工具，只需要：

1. 打开 GitHub 仓库
2. 点击 `index.html` 文件
3. 点击右上角的编辑按钮（铅笔图标）
4. 删除原有内容，粘贴新的代码
5. 点击 "Commit changes"
6. 等待 1-2 分钟即可生效

---

## 🌟 自定义域名（可选）

如果你有自己的域名，可以绑定：

1. 在仓库的 Settings → Pages 中
2. 找到 "Custom domain" 部分
3. 输入你的域名，如：`video.mydomain.com`
4. 按照提示配置 DNS 解析

---

## 🔒 隐私说明

- ✅ 所有处理都在你的**手机/浏览器本地**完成
- ✅ 视频文件**不会上传**到任何服务器
- ✅ 即使是 GitHub Pages 托管，也只是静态页面，没有后端服务器
- ✅ 完全私密，安全可靠

---

## 💡 小贴士

1. **分享给朋友**：部署后把网址发给朋友，他们也能用
2. **添加到主屏幕**：在 iPhone/Android 浏览器中，点击"分享"→"添加到主屏幕"，像 App 一样使用
3. **离线使用**：第一次加载后，部分浏览器支持离线使用

---

## ❓ 常见问题

### Q: 为什么需要部署到 GitHub Pages，不能直接打开文件？
A: 由于浏览器安全限制（CORS），WebAssembly（FFmpeg）必须通过 HTTP/HTTPS 协议加载，不能直接打开本地文件。

### Q: GitHub Pages 收费吗？
A: 完全免费！GitHub 为所有用户提供免费的静态网站托管。

### Q: 视频文件会被 GitHub 保存吗？
A: 不会！视频只在你的浏览器中处理，不会上传到 GitHub 或任何服务器。

### Q: 转换速度怎么样？
A: 取决于手机性能和视频大小。一般 1-2 分钟的视频几秒钟就能转换完成。

---

## 🎉 完成！

部署完成后，你就拥有了一个永久在线的视频转音频工具，随时随地想用就用！
