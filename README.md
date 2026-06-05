# 🍠 AI 小红书文案生成器 (皇家小虎)

## ✨ 项目简介
这是一个面向食品行业的全栈 AI 应用，能帮助内容团队将“产品信息”自动生成高转化的“小红书爆款文案”和“AI 配图”，**显著提升内容生产效率**。

## 🚀 核心功能
*   **一键生成爆款文案**：调用 DeepSeek API，自动生成种草/教程/测评三种风格文案，自带话题标签。
*   **AI 智能生成配图**：调用 SiliconFlow API，根据文案内容生成高质感美食图片。
*   **智能工作流**：
    *   **历史记录库**：所有生成结果自动保存至本地，支持一键回溯。
    *   **批量处理**：支持上传 Excel 表格，一次性生成最多 50 条文案。
    *   **一键复制**：点击按钮即可复制最终文案。

## 🛠️ 技术栈
*   **前端**：HTML5, CSS3, JavaScript (原生)
*   **后端服务**：Cloudflare Workers (用于安全地代理 API 请求)
*   **AI 模型**：
    *   **文案生成**：DeepSeek Chat
    *   **图片生成**：Tongyi-MAI/Z-Image-Turbo (SiliconFlow)
*   **数据持久化**：LocalStorage (浏览器本地存储)

## 🎥 在线体验与演示
*   **项目在线体验**：https://qsquince.github.io/ai-copywriter/  

## 📋 使用说明
1.  在线打开项目，填写“产品名称”、“核心卖点”等信息。
2.  点击“生成文案”，等待 AI 创作。
3.  点击“生成配图”，获得专属视觉素材。
4.  点击右侧历史记录，可随时调取之前的作品。
5.  (批量功能) 下载提供的 Excel 模板，填入数据后上传即可。
<img width="1219" height="923" alt="image" src="https://github.com/user-attachments/assets/5f2a0dbc-c816-468b-a275-ec7c34c340a6" />
<img width="618" height="211" alt="image" src="https://github.com/user-attachments/assets/8752f31d-70c9-49a0-bab4-32bf4c3ceb4e" />

