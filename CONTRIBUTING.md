# 贡献指南

感谢您对 Cursor Agent 数字员工团队协作系统的关注！我们欢迎各种形式的贡献。

## 🤝 如何贡献

### 1. 报告问题
如果您发现了bug或有功能建议，请：
- 在 [Issues](https://github.com/your-username/cursor-agents/issues) 中创建新的issue
- 详细描述问题或建议
- 提供复现步骤（如果是bug）

### 2. 提交代码
1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

### 3. 改进文档
- 完善README.md
- 添加使用示例
- 改进代码注释
- 翻译文档

## 📋 贡献类型

### 新增Subagent
如果您想添加新的专业角色：
1. 在 `.cursor/agents/` 目录下创建新的Subagent定义文件
2. 在 `.cursor/commands/` 目录下创建对应的命令文件
3. 在 `.cursorrules` 文件中添加新的调度规则
4. 更新README.md文档

### 改进工作流程
如果您想优化现有的工作流程：
1. 修改 `.cursorrules` 文件中的协作流程
2. 更新相关Subagent的配置
3. 测试新的工作流程
4. 更新文档说明

### 优化文档结构
如果您想改进文档组织：
1. 调整 `.cursor/docs/` 目录结构
2. 更新文档命名规范
3. 改进文档内容质量
4. 更新相关配置

## 🔧 开发环境

### 前置要求
- Cursor IDE
- Git
- 基本的Markdown编辑能力

### 本地开发
1. 克隆仓库：`git clone https://github.com/your-username/cursor-agents.git`
2. 进入目录：`cd cursor-agents`
3. 在Cursor中打开项目
4. 开始开发

## 📝 代码规范

### 文件命名
- 使用小写字母和连字符：`product_manager.md`
- 中文文档使用中文命名：`产品需求文档.md`

### 文档格式
- 使用Markdown格式
- 保持结构清晰
- 添加必要的注释

### 提交信息
- 使用清晰的提交信息
- 遵循约定式提交规范
- 例如：`feat: 添加新的Subagent`、`fix: 修复工作流程问题`

## 🎯 贡献重点

我们特别欢迎以下类型的贡献：

1. **新增专业角色**：如测试工程师、运维工程师、数据分析师等
2. **优化工作流程**：改进现有的5阶段工作流程
3. **增强用户体验**：简化使用方式，提高效率
4. **完善文档**：添加更多使用示例和最佳实践
5. **国际化支持**：添加多语言支持

## ❓ 问题反馈

如果您在贡献过程中遇到任何问题，请：
- 查看现有的 [Issues](https://github.com/your-username/cursor-agents/issues)
- 创建新的issue描述您的问题
- 联系维护者

## 📄 许可证

通过贡献代码，您同意您的贡献将在 [MIT License](LICENSE) 下发布。

---

再次感谢您的贡献！您的参与让这个项目变得更好。
