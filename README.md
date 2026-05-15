# 📓 my-notebook

> 个人技术学习与投资研究的知识笔记库，持续更新，定期同步至远程仓库。

## 项目背景

这是一个用于沉淀个人成长的笔记仓库。在日常学习技术、研究投资的过程中，零散的知识点容易遗忘，建立这个仓库的初衷是：

- 通过书写强化理解，记录思考过程
- 建立结构化的个人知识体系
- 方便日后复习检索，避免重复踩坑

---

## 目录结构

```
NoteBook/
├── CS-Fundamentals/        # 计算机基础
├── Programming-Languages/  # 编程语言
├── Backend/                # 后端开发
├── Frontend/               # 前端开发
├── DevOps/                 # 运维与工程
├── AI-ML/                  # 人工智能与机器学习
├── System-Design/          # 系统设计与架构
├── Tools/                  # 工具使用
├── Reading-Notes/          # 读书笔记
├── Interview/              # 面试题整理
└── Investment/             # 投资研究
    ├── Stock/              # 股票
    ├── Fund/               # 基金（ETF、指数基金等）
    ├── Crypto/             # 加密货币
    ├── Macro/              # 宏观经济分析
    └── Books/              # 投资相关书籍笔记
```

## 目录详细介绍

| 目录 | 说明 | 适合存放的内容 |
|------|------|---------------|
| `CS-Fundamentals` | 计算机基础 | 数据结构、算法、操作系统、计算机网络、组成原理 |
| `Programming-Languages` | 编程语言 | Python、Java、Go、SQL 等语言的语法、特性笔记 |
| `Backend` | 后端开发 | Spring、MySQL、Redis、Kafka、RPC 框架等 |
| `Frontend` | 前端开发 | HTML/CSS/JS 基础、Vue、React 等框架 |
| `DevOps` | 运维与工程 | Docker、Kubernetes、CI/CD、Linux 命令、Shell 脚本 |
| `AI-ML` | 人工智能与机器学习 | 机器学习原理、深度学习、大模型、Prompt 技巧 |
| `System-Design` | 系统设计与架构 | 分布式系统、高可用设计、DDD、架构模式 |
| `Tools` | 工具使用 | Git、IDE 技巧、命令行工具、效率软件 |
| `Reading-Notes` | 读书笔记 | 技术书籍、文章的核心观点与摘录 |
| `Interview` | 面试题整理 | 高频面试题、知识点速查、八股文整理 |
| `Investment/Stock` | 股票 | 股票分析方法、个股研究、行业研究笔记 |
| `Investment/Fund` | 基金 | 基金投资策略、ETF 与指数基金研究 |
| `Investment/Crypto` | 加密货币 | 区块链基础知识、市场分析、项目研究 |
| `Investment/Macro` | 宏观经济 | 货币政策、经济周期、全球市场分析 |
| `Investment/Books` | 投资书籍 | 投资类书籍的读书笔记与核心摘录 |

---

## 笔记规范

### 文件命名

- 使用小写字母 + 连字符，例如：`redis-basic.md`、`tcp-ip-protocol.md`
- 书籍笔记以书名命名，例如：`the-intelligent-investor.md`

### 笔记模板

每篇笔记建议包含以下结构：

```markdown
# 标题

> 一句话概括这篇笔记的核心内容

## 核心概念

## 详细笔记

## 总结 / 关键点

## 参考资料
```

### 约定

- 每个知识点尽量独立成文，避免一篇笔记过于冗长
- 图片统一放在同级 `assets/` 目录下
- 临时草稿以 `draft-` 开头命名

---

## 提交工作流

### 日常提交

新增或修改笔记后，执行以下命令同步到远程仓库：

```bash
# 查看变动文件
git status

# 添加所有变动
git add .

# 提交（说明本次新增/修改了什么）
git commit -m "新增 Redis 基础笔记"

# 推送到远程
git push
```

### 提交信息规范

```
新增 xxx 笔记
更新 xxx 笔记
完善 xxx 内容
```
