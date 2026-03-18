# Agent Skills Collection

一套用于增强 AI Agent 能力的专业化技能集合。

## Skills 列表

### 🌐 浏览器自动化

| Skill | 描述 |
|-------|------|
| **[agent-browser](./agent-browser/)** | 浏览器自动化 CLI，支持网页导航、表单填写、截图、数据抓取、Web 应用测试等。基于 Chrome/Chromium 通过 CDP 直接控制。 |
| **[chrome-devtools](./chrome-devtools/)** | 使用 Chrome DevTools MCP 进行专家级浏览器自动化、调试和性能分析。支持网络流量分析、性能追踪、JavaScript 调试。 |
| **[playwright-skill](./playwright-skill/)** | Playwright 浏览器自动化工具，自动检测开发服务器，支持响应式测试、登录流程测试等。 |
| **[webapp-testing](./webapp-testing/)** | 本地 Web 应用测试工具包，支持前端功能验证、UI 调试、截图捕获、浏览器日志查看。 |

### 📝 文档处理

| Skill | 描述 |
|-------|------|
| **[docx](./docx/)** | Word 文档 (.docx) 创建、编辑和分析。支持目录、标题、页码、页眉页脚、表格、图片插入、修订追踪等。 |
| **[sync-docs](./sync-docs/)** | 自动同步 Git 变更到 AGENTS.md/MODULE.md 文档，防止代码与文档契约脱节。支持内容级和元数据级更新识别。 |

### 💻 代码质量

| Skill | 描述 |
|-------|------|
| **[code-review-excellence](./code-review-excellence/)** | 代码评审最佳实践指南。提供建设性反馈技巧、评审流程、安全检查清单、团队协作建议。 |
| **[receiving-code-review](./receiving-code-review/)** | 接收代码评审反馈的最佳实践。强调技术验证而非盲目实现，处理不清晰反馈、合理反驳。 |
| **[git-commit](./git-commit/)** | Git 提交工作流自动化。自动分析 diff 生成规范的 Conventional Commit 消息，智能文件暂存。 |

### 🎨 设计与创意

| Skill | 描述 |
|-------|------|
| **[frontend-design](./frontend-design/)** | 创建高质量、生产级前端界面。避免通用 AI 美学，支持网站、落地页、仪表盘、React 组件等。 |
| **[simple](./simple/)** | 创意和架构工作前的轻量级头脑风暴流程。快速从想法到可执行方向，适合功能设计、组件创建等。 |

### 🛠 工具与扩展

| Skill | 描述 |
|-------|------|
| **[find-skills](./find-skills/)** | 帮助用户发现和安装 agent skills。搜索 skills.sh 生态系统的技能包。 |
| **[skill-creator](./skill-creator/)** | 创建、修改和优化 skills。支持测试用例运行、性能基准测试、描述优化等完整开发流程。 |

## 安装使用

每个 skill 目录包含 `SKILL.md` 文件，定义了技能的元数据和具体指令。将 skill 目录放置在 agent 的 skills 路径下即可自动加载。

```bash
# 示例：克隆到本地
git clone https://github.com/jiangjianzeng/skills.git

# 或单独安装某个 skill
npx skills add <owner/repo@skill-name>
```

## Skill 结构

```
skill-name/
├── SKILL.md          # 必需：技能元数据和指令
├── scripts/          # 可选：执行脚本
├── references/       # 可选：参考文档
├── assets/           # 可选：资源文件
└── templates/        # 可选：模板文件
```

## 贡献

欢迎贡献新的 skills 或改进现有 skills。请参考 [skill-creator](./skill-creator/) 了解如何创建高质量的 skill。

## 许可证

各 skill 的许可证信息请参阅各自的 LICENSE 文件或 SKILL.md 中的声明。