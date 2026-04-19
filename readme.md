# Team Toolkit

团队标准开发工具包，提供代码审查、测试、部署、安全扫描一体化解决方案。

## 安装

\```bash
/plugin install team-toolkit@our-company
\```

## 功能

### 命令

| 命令 | 说明 |
|------|------|
| `/review [target]` | 代码审查 |
| `/test [scope]` | 运行测试 |
| `/deploy [env]` | 部署应用 |

### 代理

| 代理 | 说明 |
|------|------|
| `security-scanner` | 安全漏洞扫描 |
| `quick-fix` | 快速修复小问题 |

### Skills

| Skill | 说明 |
|-------|------|
| `react-patterns` | React 最佳实践 |

### MCP 服务器

| 服务器 | 说明 |
|--------|------|
| `postgres` | 数据库查询 |
| `github` | GitHub API |

## 环境变量

\```bash
# 数据库连接（用于 postgres MCP）
export DATABASE_URL="postgres://..."

# GitHub Token（用于 github MCP）
export GITHUB_TOKEN="ghp_..."
\```

## 更新日志

### v2.0.0

- 新增：`/deploy` 命令
- 新增：`security-scanner` 代理
- 改进：`/review` 输出格式
- 修复：Hook 脚本兼容性问题

### v1.0.0

- 初始版本

## 贡献

欢迎提交 PR！请确保：
1. 代码通过 lint 检查
2. 更新相关文档
3. 添加测试（如适用）

## 许可证

MIT