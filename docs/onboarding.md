# 🚀 新手指南

欢迎加入游戏化学习小组！这份指南将帮助你快速上手。

## 📋 第一步：准备工作

### 1.1 创建 GitHub 账号

如果你还没有 GitHub 账号：
1. 访问 https://github.com
2. 点击 "Sign up"
3. 完成注册流程

### 1.2 安装必要工具

**Obsidian**（必需）
- 下载：https://obsidian.md/
- 安装并启动

**Git**（推荐）
```bash
# macOS
brew install git

# Windows
# 下载 https://git-scm.com/download/win

# Linux
sudo apt-get install git
```

## 📂 第二步：克隆仓库

```bash
# 克隆项目仓库
git clone https://github.com/your-org/gamified-learning-group.git

# 进入项目目录
cd gamified-learning-group
```

## 📝 第三步：设置 Obsidian

### 3.1 打开 Vault

1. 打开 Obsidian
2. 点击 "Open folder as vault"
3. 选择 `gamified-learning-group/obsidian-template` 文件夹

### 3.2 安装插件（可选但推荐）

**Templater** - 自动化模板
1. 打开 Settings → Community plugins
2. 关闭 Safe mode
3. 点击 Browse
4. 搜索 "Templater"
5. 安装并启用

**Dataview** - 数据查询
1. 同样在 Community plugins 中
2. 搜索 "Dataview"
3. 安装并启用

### 3.3 配置模板

1. 打开 Settings → Templater
2. 设置 "Template folder location" 为 `Templates`
3. 启用 "Trigger Templater on new file creation"

## 🎯 第四步：创建第一个任务

### 4.1 在 GitHub 上创建

1. 访问项目仓库
2. 点击 Issues → New issue
3. 选择 "🎯 学习任务" 模板
4. 填写任务信息：
   - 任务名称：例如 "学习 Python 基础"
   - 难度：选择适合你的难度
   - 描述：详细描述要学什么
5. 点击 Submit new issue

### 4.2 在 Obsidian 中记录

1. 在 Obsidian 中，按 `Ctrl/Cmd + N` 创建新笔记
2. 使用 Daily Note 模板
3. 记录今天的学习内容

## 💻 第五步：提交你的学习成果

```bash
# 添加修改的文件
git add .

# 提交修改
git commit -m "📝 今日学习：Python 基础"

# 推送到远程
git push origin main
```

## 🎮 第六步：查看积分

- 每次提交后，系统会自动计算积分
- 查看 `LEADERBOARD.md` 文件了解排名
- 在 GitHub Actions 中查看详细日志

## 💡 常见问题

### Q: 我不会用 Git 怎么办？
A: 可以先使用 GitHub 网页版创建 Issues，Obsidian 的笔记可以稍后同步。

### Q: Obsidian 的模板不会用？
A: 可以直接复制模板内容，手动填写。随着使用会逐渐熟悉。

### Q: 积分没有更新？
A: GitHub Actions 可能需要几分钟。如果长时间没更新，联系管理员。

### Q: 可以创建什么类型的任务？
A: 任何学习相关的都可以：读书、看视频、做项目、练习技能等。

## 🎯 建议的学习节奏

- **每天**：
  - 创建/完成 1-2 个任务
  - 写 Daily Note
  - 参与讨论

- **每周**：
  - 完成 1 个中等难度项目
  - 回顾本周学习内容
  - 查看排行榜

- **每月**：
  - 完成 1 个大型项目
  - 总结学习成果
  - 设定下月目标

## 📞 需要帮助？

- 在 GitHub Issues 中创建问题
- 在讨论区提问
- 联系项目管理员

祝你学习愉快！🎉
