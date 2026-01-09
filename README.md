# JSON Tree Viewer - JSON 树形结构解析器

## 项目介绍
一个轻量级、美观且功能完善的 JSON 树形结构解析器，支持文件上传、URL 拉取和直接输入三种方式导入 JSON 数据，并以可视化的树形结构展示，支持节点折叠/展开、路径复制和关键词搜索，适配移动端和桌面端。

## 功能特点
- 📥 **多源导入**：支持文件上传、URL 拉取、直接输入三种 JSON 导入方式
- 🌳 **树形可视化**：以层级树形结构展示 JSON 数据，清晰直观
- 🔍 **实时搜索**：支持关键词搜索并高亮匹配节点
- 📋 **路径复制**：一键复制任意节点的完整路径
- 📱 **响应式设计**：完美适配桌面端和移动端
- 🎨 **美观界面**：渐变风格 UI，优雅的交互动画
- 🚀 **零依赖**：纯原生 HTML/CSS/JS 实现，无需任何框架

## 快速开始
### 方式 1：直接使用
1. 克隆本仓库
   ```bash
   git clone https://github.com/EndlessPixel/JSON-Tree-Viewer.git
   ```
2. 打开 `index.html` 文件即可使用

### 方式 2：URL 自动加载（进阶）
可以通过 URL 参数自动加载指定的 JSON 接口：
```
?url=https://api.example.com/data.json
```

## 使用说明
1. **选择导入方式**：文件上传 / URL 拉取 / 直接输入
2. **导入 JSON 数据**：
   - 文件上传：选择 `.json` 格式文件
   - URL 拉取：输入有效的 JSON 接口地址（需支持跨域）
   - 直接输入：粘贴或输入标准 JSON 文本
3. **点击「导入并解析」** 按钮
4. **交互操作**：
   - 点击节点前的 `+/-` 按钮折叠/展开子节点
   - 悬停节点显示「复制」按钮，点击复制节点路径
   - 使用搜索框实时搜索关键词，匹配节点会高亮显示

## 截图展示
<img width="1300" height="5643" alt="image" src="https://github.com/user-attachments/assets/2a1893e3-7cc6-44b9-be13-54bf973d385f" />

## 技术栈
- HTML5 (语义化标签、响应式布局)
- CSS3 (Flex 布局、渐变、动画、媒体查询)
- Vanilla JavaScript (原生 JS，无框架依赖)

## 许可证
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件
