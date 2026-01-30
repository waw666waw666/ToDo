# Do - 极简待办与成就记录助手

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Android%20|%20Web-green.svg)
![AI-Powered](https://img.shields.io/badge/Built%20with-Trae%20Gemini--3--Pro-blueviolet)

`Do` 是一款专为移动端设计的极简待办事项（To-Do）与成就记录（Done）工具。本项目由一位编程新手在 **Trae** AI 助手的辅助下，使用 **Gemini-3-Pro-Preview** 模型，历时约 **12 小时**，经过 **10 余个版本** 的迭代开发而成。

通过将纯 HTML 项目转换成 APK，它实现了从 Web 构思到手机 App 实用的完整闭环。

---

## 🌟 核心功能

- **双维度管理**：
  - **To Do（待办）**：记录计划中的任务，支持设置时间、上传图片。
  - **Do（成就）**：展示已完成的事项，将“完成任务”转化为“积累成就”，提供正向反馈。
- **智能交互**：
  - **侧滑删除**：流畅的拟物化侧滑手势，快速清理任务。
  - **长按排序**：集成 SortableJS，支持在移动端通过长按拖拽灵活调整优先级。
  - **自动时间管理**：支持“设为当前”快捷填入，并能根据日期自动识别星期几。
- **多媒体支持**：
  - 支持为每个事项添加多张图片（Base64 存储）。
  - 内置全屏图片查看器，支持沉浸式浏览。
- **极致视觉体验**：
  - 基于 **ColorOS** 设计语言，采用大圆角卡片、毛玻璃滤镜（Backdrop Blur）及优雅的过渡动画。
  - 完美适配手机状态栏（Safe Area），支持深色模式视觉友好。
- **离线存储**：
  - 基于 `localStorage` 实现数据持久化，无需联网，隐私安全。

---

## 🛠️ 技术栈

- **编辑器**：[Trae](https://www.trae.ai/) (AI 驱动的下一代 IDE)
- **AI 模型**：Gemini-3-Pro-Preview
- **前端框架**：Tailwind CSS (响应式布局与样式)
- **交互增强**：SortableJS (移动端拖拽排序)
- **图标库**：Font Awesome 6.4.0
- **打包工具**：[Demo2APK](https://demo2apk.lasuo.ai/) (将 HTML 项目一键转为 Android APK)

---

## 🚀 开发故事

这是一个关于“AI 如何赋能个体创作”的小故事：
1. **起步**：作为一名编程新手，我希望拥有一个符合自己审美且简单的待办工具。
2. **协作**：在 Trae 环境下，通过与 Gemini-3-Pro 模型进行深度对话，我们从一个简单的列表开始，不断加入侧滑、排序、图片上传等复杂功能。
3. **迭代**：在 12 小时的开发过程中，我们解决了移动端适配、手势冲突、数据存储等 10 多个版本的技术难题。
4. **转化**：最终，我通过 `demo2apk.lasuo.ai` 将这个 HTML 页面变成了一个真正的手机 App，装进了自己的口袋。

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 协议。




