# 🎮 游戏化学习小组

一个结合了 **GitHub 协作** 和 **Obsidian 笔记** 的游戏化学习系统。

## 🌟 特性

- 🎯 **任务系统** - 通过 GitHub Issues 分配和追踪学习任务
- 📊 **积分系统** - 自动计算贡献积分
- 🏆 **排行榜** - 实时显示学习进度和排名
- 📚 **笔记管理** - 使用 Obsidian 记录学习内容
- 🎁 **奖励机制** - 完成任务获得积分和徽章

## 🚀 快速开始

### 1. 加入项目

1. 联系项目管理员获取仓库访问权限
2. 克隆仓库到本地:
   ```bash
   git clone https://github.com/your-org/gamified-learning-group.git
   ```

### 2. 设置 Obsidian

1. 下载并安装 [Obsidian](https://obsidian.md/)
2. 打开 Obsidian，选择 "Open folder as vault"
3. 选择 `obsidian-template` 文件夹
4. 安装推荐插件:
   - **Templater** - 模板管理
   - **Dataview** - 数据查询
   - **Git** - Git 同步（可选）

### 3. 创建你的第一个任务

1. 进入 GitHub Issues
2. 点击 "New Issue"
3. 选择 "🎯 学习任务" 模板
4. 填写任务信息并提交

## 📊 积分规则

| 行为 | 积分 | 说明 |
|------|------|------|
| 创建任务 | +5 | 创建一个新的学习任务 |
| 完成任务 | +15 | 完成任务并关闭 Issue |
| 提交 PR | +10 | 提交学习笔记或代码 |
| PR 被合并 | +25 | 贡献被采纳 |
| 参与讨论 | +3 | 在 Issue/PR 中评论 |
| 提交 Commit | +5 | 每次代码提交 |

## 🏆 等级系统

| 等级 | 积分范围 | 称号 |
|------|----------|------|
| Lv.1 | 0-99 | 新手 |
| Lv.2 | 100-199 | 学徒 |
| Lv.3 | 200-299 | 进阶者 |
| Lv.4 | 300-499 | 专家 |
| Lv.5+ | 500+ | 大师 ⭐ |

## 📁 仓库结构

```
.
├── .github/
│   ├── workflows/          # GitHub Actions 自动化
│   └── ISSUE_TEMPLATE/     # Issue 模板
├── obsidian-template/       # Obsidian 模板
│   ├── Daily Notes/        # 每日笔记
│   ├── Projects/           # 项目笔记
│   └── Templates/          # 笔记模板
├── docs/                   # 文档
├── points-log.json         # 积分记录（自动生成）
└── LEADERBOARD.md          # 排行榜（自动生成）
```

## 🎮 工作流程

### 每日学习流程

1. **创建今日任务** (GitHub Issue)
2. **学习并记录** (Obsidian Daily Note)
3. **提交进度** (Git Commit)
4. **获得积分** (自动计算)

### 项目学习流程

1. **创建项目** (GitHub Issue)
2. **规划学习路径** (Obsidian Project Note)
3. **分阶段完成** (多个 Task Issues)
4. **总结成果** (PR + 合并)
5. **获得奖励** (大量积分)

## 📖 文档

- [游戏规则](docs/rules.md)
- [新手指南](docs/onboarding.md)
- [Obsidian 使用指南](docs/obsidian-guide.md)

## 🤝 贡献

欢迎提交 Issue 和 PR 来改进这个系统！

## 📜 许可证

MIT License
