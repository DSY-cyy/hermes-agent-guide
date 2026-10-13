# Hermes Agent 六步闯关学习手册

> 从安装到工具调用，循序渐进掌握自主 AI Agent

面向零基础学习者的交互式闯关学习手册，六步递进式学习 Hermes 自主 AI Agent 的核心用法。完成当前关自动解锁下一关，边学边练，每一步都有明确的产出。

## ✨ 功能特性

- **闯关式学习**：六关递进，完成当前关自动解锁下一关
- **进度持久化**：学习进度自动保存在浏览器本地，刷新不丢失
- **交互式路线图**：可视化学习路径，一目了然当前进度
- **代码一键复制**：所有命令和代码块支持一键复制
- **响应式设计**：完美适配桌面、平板、手机等各种设备
- **完成庆祝效果**：全部通关后触发彩带庆祝动画

## 📚 六关内容概览

| 关卡 | 标题 | 核心内容 | 通关标准 |
|------|------|----------|----------|
| Step 1 | Installation 安装 | 4 类安装路径、安装器原理、安装后验证与故障排查 | `hermes` 能正常启动 |
| Step 2 | Quickstart 快速上手 | 初始化配置、首次对话、CLI/TUI 界面、会话恢复 | 能正常与 Hermes 对话 |
| Step 3 | 模型配置 | Provider/Model/Base URL/API Key 四要素、10+ 平台配置 | 成功配置模型 API 并对话 |
| Step 4 | CLI 命令 | 斜杠命令体系、会话管理、状态栏解读、快捷键 | 能查看模型、工具和 Context |
| Step 5 | 配置文件 | config.yaml 与 .env 结构、配置优先级、终端后端 | 能解释普通配置与 Secret 区别 |
| Step 6 | 工具调用 | Tool Calling 原理、6 大工具分类、工具集机制、实操案例 | 完成读文件→处理→输出完整流程 |

## 🌐 在线访问

- **国内推荐（豆包 HTML）**：https://4m8y363sm2nmy.doubaoapps.com/app/app_17fz9anwmys
- **GitHub Pages**：https://dsy-cyy.github.io/hermes-agent-guide/

## 🛠 技术栈

- **HTML5** + **CSS3** + **原生 JavaScript**（单文件，无构建依赖）
- **Tailwind CSS**（CDN 引入）
- **localStorage**（进度持久化）
- 部署于 **GitHub Pages** / 豆包 HTML 平台

## 🚀 本地运行

无需任何构建工具，直接用浏览器打开即可：

```bash
# 克隆仓库
git clone https://github.com/DSY-cyy/hermes-agent-guide.git

# 进入目录
cd hermes-agent-guide

# 直接用浏览器打开
# Windows: start index.html
# macOS: open index.html
# Linux: xdg-open index.html
```

或者启动一个本地 HTTP 服务器：

```bash
# Python 3
python -m http.server 8080

# 然后访问 http://localhost:8080
```

## 📁 项目结构

```
hermes-agent-guide/
├── index.html      # 主页面（含全部 CSS/JS，单文件自包含）
└── README.md       # 项目说明文档
```

## 📖 参考资料

- [Hermes Agent 官方文档](https://hermes-agent.nousresearch.com/docs)
- [OpenAI Function Calling 文档](https://platform.openai.com/docs/guides/function-calling)
- [Anthropic Tool Use 文档](https://docs.anthropic.com/en/docs/build-with-claude/tool-use)
- [ReAct: Synergizing Reasoning and Acting](https://arxiv.org/abs/2210.03629)

## 📄 License

MIT License
