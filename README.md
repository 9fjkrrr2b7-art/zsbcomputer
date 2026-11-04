# zsbcomputer — 专升本计算机 0 基础 AI 教练 Skill

一个面向 **0 基础学生** 的专升本计算机备考训练技能（Skill），适配 [WorkBuddy](https://www.workbuddy.cn) 等支持 Agent Skills 的 AI 助手。

融合三位可溯源名师的教学法，按「**入门破冰 → 讲透为什么 → 命题提分**」三位一体闭环带学，并以**命题人/阅卷人双视角**严格自检出题与阅卷。

## ✨ 功能

- **零基础带学**：诊断 → 讲解 → 出题 → 阅卷 → 错题复盘的完整闭环
- **三位名师方法论融合**：
  - 玄冰（库课）——生活类比 + 口诀记忆，先"听得懂"
  - 邵增珍/邵博士（廿书教育）——讲透"为什么"，知识"立得住"
  - 公方胜（海纳教育）——命题视角 + 真题 + 错题复盘，分数"拿得稳"
- **严格出题自检**：内置命题人/阅卷人评判标准与 7 条自检打分卡，绝不出"带病题"
- **内置题库**：312 题山东专升本计算机真题（按考纲十章组织，每题含答案+解析）+ 历年真题示例
- **教案/PPT 赋能**：写教案或做 PPT 时，自动在导入/新授/收尾三段附上对应名师的授课思路
- **考纲适配**：山东统考版式，Windows 10 + Office 2016，覆盖 11 章

## 📦 安装

### WorkBuddy 用户

1. 克隆或下载本仓库：

   ```bash
   git clone https://github.com/<你的用户名>/zsbcomputer.git
   ```

2. 把**整个仓库文件夹**复制到技能目录（Windows 为 `%USERPROFILE%\.workbuddy\skills\`，macOS/Linux 为 `~/.workbuddy/skills/`）：

   ```bash
   # Windows (Git Bash) 示例
   cp -r zsbcomputer ~/.workbuddy/skills/zsb-computer-coach
   ```

   > 注意：必须是**真实目录**，不要用符号链接/junction，否则技能扫描器会跳过。

3. 重启 WorkBuddy（或新开会话），技能即可生效。

### 目录结构

```
zsbcomputer/
├── SKILL.md                      # 技能主文件：三位一体教练闭环 + 命题/阅卷双视角
├── README.md
├── LICENSE
└── references/
    ├── methodology.md            # 三位名师方法论卡片 + 0 基础学习地图
    ├── exam-outline.md           # 山东考纲 11 章考点（Win10 + Office2016）
    ├── question-rubric.md        # 命题人/阅卷人评判标准 + 自检打分卡
    ├── bank-template.md          # 出题模板与样例
    ├── question-bank.md          # 312 题真题库（按十章组织，含答案解析）
    └── teaching-injection.md     # 教案/PPT 名师思路注入范式
```

## 💬 使用示例

安装后直接在对话里说：

- 「学一下第 1 章进制转换」→ 走诊断→讲解→练习闭环
- 「按第 3 章出 10 道单选题，过一遍自检卡」→ 严格命题出题
- 「判一下我这道题错在哪」→ 阅卷人视角错题复盘
- 「写第 3 章操作系统教案，导入用玄冰、原理用邵博士、收尾用公方胜」→ 教案自动附名师思路
- 「做进制转换 PPT，每页备注写名师怎么讲」→ PPT 备注附名师思路卡

## 🎯 适用人群

- 专升本（尤其山东统考）计算机备考的 0 基础学生
- 需要按山东考纲命题出题的教师
- 想在教案/PPT 中融入名师教学法的授课者

## 📄 许可

MIT License，题库数据源自开源项目 [thy56/tiku](https://github.com/thy56/tiku)（山东专升本·四科学习站）。
