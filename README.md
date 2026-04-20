# Seedance2API-APP

[中文](#中文) | [English](#english)

---

## 中文

这是一个单文件网页应用，核心就是 [index.html](C:\Users\Powerful5090\Desktop\Seedance2API-APP\index.html)。

打开 `index.html` 就能使用，主要功能包括：

- Seedance 视频生成
- 字幕擦除
- 图片 / 视频 / 音频参考素材管理
- 左侧资源库分组管理
- 任务轮询、结果预览、历史复用

### 功能说明

- 提示词编辑器支持 `@` 引用素材
- 参考素材支持：
  - URL 添加
  - `ASSET_ID` 添加
  - 拖拽上传
  - 点击上传
  - `Ctrl+V` 粘贴上传
- 左侧资源库支持：
  - 创建资源组
  - 拉取资源
  - 分组收起 / 展开
  - 分组刷新
  - 组内上传素材
  - 组内素材直接加入生成器
- 资源组内上传支持：
  - 拖拽
  - 点击选择文件
  - 激活组后 `Ctrl+V` 粘贴
- 上传素材后会自动轮询状态
- 任务完成后默认自动下载

### 使用方式

1. 打开 [index.html](C:\Users\Powerful5090\Desktop\Seedance2API-APP\index.html)
2. 在设置里填写所需密钥
3. 添加提示词和素材
4. 提交任务
5. 在右侧查看任务状态和结果

### 说明

- 所有界面、样式和逻辑都在 `index.html` 中
- 页面配置、历史记录、任务记录和日志保存在浏览器本地

---

## English

This project is a single-file web app, centered on [index.html](C:\Users\Powerful5090\Desktop\Seedance2API-APP\index.html).

Open `index.html` and use it directly.

### Features

- Seedance video generation
- Subtitle erasing
- Image / video / audio reference asset handling
- Left-side grouped asset library
- Task polling, preview, and history reuse

- Prompt editor with `@` asset mentions
- Asset input supports:
  - URL
  - `ASSET_ID`
  - Drag and drop
  - Click upload
  - `Ctrl+V` paste
- Asset groups support:
  - Create group
  - Pull assets
  - Collapse / expand
  - Refresh group
  - Upload inside group
  - Add group assets into the generator
- Uploaded assets are polled automatically
- Auto-download is enabled by default after completion

### Usage

1. Open [index.html](C:\Users\Powerful5090\Desktop\Seedance2API-APP\index.html)
2. Fill in required keys in settings
3. Add prompt and assets
4. Submit the task
5. Track status and results in the right panel

### Notes

- All UI, styles, and logic are inside `index.html`
- Settings, history, task records, and logs are stored locally in the browser
