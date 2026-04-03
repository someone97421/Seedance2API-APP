# Seedance 视频生成器 (Seedance Video Generator)

[中文](#中文) | [English](#english)

---

<h2 id="中文">🇨🇳 中文</h2>

**Seedance 视频生成器** 是一个基于浏览器的单文件 Web 应用，专门用于调用火山引擎（Volcengine）的 Seedance 视频生成 API，提供强大、直观且易于管理的视频生成体验。

### 🌟 核心功能

- 🎨 **高级提示词编辑器**：支持类似社交媒体的 `@` 引用功能。可以通过输入 `@` 或点击按钮，在提示词中直接引用上传的图片、视频或音频素材（例如：`@img1`、`@video1`）。
- 📂 **富媒体素材管理**：
  - 支持**图片**、**视频**和**音频**三种类型的参考素材。
  - 支持 **拖拽上传** 和 **URL 链接** 导入。
  - 自动将上传的本地图片、视频和音频借助 Litterbox 临时转换并托管为公开 URL（由于 API 要求）。
- ⚡ **多任务并发与轮询**：
  - 采用了基于任务流的架构，支持提交多个生成任务并进行并发管理。
  - 右侧拥有专门的**任务记录面板**，实时监控各个任务的状态（排队、运行中、失败、成功）。
  - 支持点击 **🐛 调试** 展开查看完整的 API 请求和响应日志，方便排错。
- 📜 **生成历史与一键复用**：
  - 任务成功后，带视频预览的历史记录会保存在页面底部的历史网格中。
  - 提供 **🔄 复用** 按钮，一键恢复该条历史的所有素材、提示词及参数设定，方便在此基础上微调后重新生成。
- ⚙️ **完整的本地配置存储**：
  - 支持自定义 API Base URL、API Key，以及 Litterbox 文件随时过期时间。
  - 支持调整所有 API 参数（模型、分辨率、画幅比例、时长等）。
  - 所有配置和历史记录安全存储在浏览器的 `localStorage` 中。

### 🚀 快速开始

1. **获取 API 凭证**：获取你的火山引擎 Seedance 视频生成大模型 API Key。
2. **Litterbox 免配置上传**：默认集成 Litterbox 匿名缓存服务，无需任何 API Key，可直接在本地拖拽上传图片、视频和音频用于生成。
3. **运行应用**：本应用是一个纯粹的前端项目。直接在浏览器中双击打开 `seedance-video-generator.html` 即可使用。
4. **填写配置**：展开顶部的【折叠配置区】，填入你的 API Key。

---

<h2 id="english">🇬🇧 English</h2>

**Seedance Video Generator** is a browser-based, single-file web application specifically designed to interface with Volcengine's Seedance Video Generation API. It offers a powerful, intuitive, and highly manageable video generation workflow.

### 🌟 Key Features

- 🎨 **Advanced Prompt Editor**: Features a social-media-style `@` mention system. You can easily reference uploaded images, videos, or audio assets directly in your prompt text by typing `@` or clicking the mention button (e.g., `@img1`, `@video1`).
- 📂 **Rich Media Asset Management**:
  - Supports three types of reference assets: **Images**, **Videos**, and **Audio**.
  - Allows seamless **Drag-and-Drop** uploading as well as direct **URL importing**.
  - Automatically hosts local image, video, and audio uploads via the Litterbox service (as the Seedance API requires public URLs).
- ⚡ **Concurrent Multi-Task Management**:
  - Built with a task-based architecture, allowing you to submit and manage multiple generation tasks concurrently.
  - Features a dedicated **Task Record Panel** on the right sidebar to track the real-time status of all your tasks (queued, running, failed, succeeded).
  - Includes a **🐛 Debug** toggle for each task to expand and inspect the full API request and response JSON logs for easy troubleshooting.
- 📜 **Generation History & One-Click Reuse**:
  - Upon task completion, records containing video previews are saved in the history grid at the bottom of the page.
  - Click the **🔄 Reuse** button on any history item to instantly restore all its assets, prompts, and parameters, allowing you to tweak and re-generate easily.
- ⚙️ **Persistent Local Storage**:
  - Customizable API Base URL, API Key, and Litterbox file expiration time.
  - Full control over all API generation parameters (Model, Resolution, Aspect Ratio, Duration, etc.).
  - All configurations, active tasks, and history are securely persisted in your browser's `localStorage`.

### 🚀 Quick Start

1. **Obtain API Credentials**: Get your API Key for the Volcengine Seedance Video Generation model.
2. **Litterbox Zero-Config Uploads**: Built-in Litterbox anonymous hosting service allows local drag-and-drop uploads of images, videos, and audio without any API Key.
3. **Run the App**: This is a pure frontend application. Simple double-click `seedance-video-generator.html` to open it in your browser.
4. **Configure**: Expand the configuration section at the top and enter your API Key to get started.
