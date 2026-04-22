# Gemini 仿 Claude 主题

一个用于 Stylus 的 CSS 样式，旨在将 Google Gemini 的界面深度复刻为 Claude 的简约纸质风格（衬线字体、暖白配色及沉浸式对话布局）。仅支持浅色模式。

<img width="1710" height="988" alt="image-20260422191252294" src="https://github.com/user-attachments/assets/62691384-6015-4437-b986-86820db25113" />

<img width="988" height="993" alt="image-20260422191427680" src="https://github.com/user-attachments/assets/e8fa0a7c-8afe-4b06-8441-3cfa5b369328" />

## 主题改动

- 将 Gemini 默认偏亮的背景改成更接近 Claude 的暖白色调
- 将整体排版调整为更偏衬线字体的阅读风格
- 优化聊天消息区域的间距与视觉层级
- 重绘代码块样式，改为更柔和的中性色
- 调整左侧边栏与菜单面板的视觉效果
- 隐藏部分页脚和免责声明相关界面元素

## 文件

- `Claude-like-Gemini.css`

## 使用方法

这个样式文件适合配合支持自定义 CSS 注入的浏览器扩展使用，例如：

- Stylus
- 支持 CSS 的扩展
- 可在 Gemini 网页上加载自定义样式的其他工具

基本步骤：

1. 安装一个支持自定义 CSS 的浏览器扩展。
2. 新建一个只作用于 Gemini 的样式。
3. 粘贴 `Claude-like-Gemini.css` 的全部内容。
4. 保存后刷新 Gemini 页面。

## 注意事项

- 这个主题依赖 Gemini 当前的 DOM 结构和类名。
- 如果 Google 后续修改页面结构，部分选择器可能会失效。
- 这个项目与 Anthropic、Claude、Google、Gemini 没有关联。

## 许可证

本项目采用 `MIT` 许可证。

这表示你可以自由使用、修改、分发和商用，但需要保留原始许可证声明。

许可证全文见仓库中的 `LICENSE` 文件。
